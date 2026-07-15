# Instructions

- Following Playwright test failed.
- Explain why, be concise, respect Playwright best practices.
- Provide a snippet of code with the fix, if possible.

# Test info

- Name: regression/EF-002-installation-cases.spec.ts >> EF-002 installation cases (data-driven) >> CONSUMER-AFTER-START-NEW — Consumer + After-Install: transfer+install on customer vehicle 1 -> 'Start New Installation' -> transfer+install on vehicle 2 -> verify on Customer List @EF-002 @installation
- Location: tests/regression/EF-002-installation-cases.spec.ts:295:9

# Error details

```
Test timeout of 70000ms exceeded.
```

# Page snapshot

```yaml
- generic [ref=e2]:
  - banner [ref=e3]:
    - generic [ref=e4]:
      - button [ref=e6] [cursor=pointer]
      - generic [ref=e11]:
        - link "Organization Logo" [ref=e12] [cursor=pointer]:
          - /url: /v2
          - img "Organization Logo" [ref=e13]
        - generic [ref=e17]:
          - textbox "Search VIN, Stock, Device ..." [ref=e18]
          - img [ref=e20]
      - generic [ref=e22]:
        - generic [ref=e25]:
          - heading "Current Time (PST)" [level=6] [ref=e26]
          - heading "13:59:49" [level=4] [ref=e27]
        - generic [ref=e29] [cursor=pointer]: IT
  - main [ref=e30]:
    - generic [ref=e32]:
      - generic [ref=e33]:
        - generic [ref=e34]:
          - heading "Customer List" [level=3] [ref=e36]
          - generic [ref=e37]:
            - generic [ref=e40]:
              - textbox "Search here..." [ref=e41]: rafael.medina1mkbkew@example.com
              - img [ref=e43]
              - button "Clear search" [ref=e46] [cursor=pointer]:
                - img [ref=e47]
            - button "Show Filters" [ref=e50] [cursor=pointer]:
              - img [ref=e51]
            - button [ref=e57] [cursor=pointer]:
              - img [ref=e58]
            - button "Export" [ref=e62] [cursor=pointer]:
              - img [ref=e63]
            - button "Actions" [ref=e66] [cursor=pointer]:
              - img [ref=e67]
        - generic [ref=e69]:
          - button "Dealership James Patrick" [ref=e72] [cursor=pointer]:
            - generic [ref=e73]: Dealership
            - generic [ref=e75]:
              - generic [ref=e76]: James Patrick
              - img [ref=e77]
          - button "Account" [ref=e81] [cursor=pointer]:
            - generic [ref=e82]: Account
          - button "Customer Status Active" [ref=e85] [cursor=pointer]:
            - generic [ref=e86]: Customer Status
            - generic [ref=e88]:
              - generic [ref=e89]: Active
              - img [ref=e90]
      - generic [ref=e93]:
        - table [ref=e95]:
          - rowgroup [ref=e96]:
            - row "Customer Name Contact Details" [ref=e97]:
              - columnheader [ref=e98]
              - columnheader "Customer Name" [ref=e99]:
                - generic [ref=e100] [cursor=pointer]:
                  - generic [ref=e101]: Customer Name
                  - img [ref=e102]
              - columnheader "Contact Details" [ref=e105]:
                - generic [ref=e106] [cursor=pointer]:
                  - generic [ref=e107]: Contact Details
                  - img [ref=e108]
          - rowgroup [ref=e111]:
            - row "Rafael Medinamkbkew rafael.medina1mkbkew@example.com -" [ref=e112]:
              - cell [ref=e113]:
                - img [ref=e115]
              - cell "Rafael Medinamkbkew" [ref=e117]:
                - generic [ref=e119] [cursor=pointer]: Rafael Medinamkbkew
              - cell "rafael.medina1mkbkew@example.com -" [ref=e120]:
                - generic [ref=e121]:
                  - generic [ref=e122]: rafael.medina1mkbkew@example.com
                  - generic [ref=e124]: "-"
            - row [ref=e125]:
              - cell [ref=e126]
        - generic [ref=e128]:
          - generic [ref=e129]:
            - generic [ref=e130]: Show
            - generic [ref=e132]:
              - combobox [ref=e133]:
                - option "15"
                - option "25" [selected]
                - option "50"
                - option "100"
              - generic:
                - img
            - generic [ref=e134]: entries
          - generic [ref=e136]:
            - button [disabled] [ref=e137]:
              - img [ref=e138]
            - button "1" [ref=e140] [cursor=pointer]
            - button [disabled] [ref=e141]:
              - img [ref=e142]
          - generic [ref=e144]: 1 - 1 of 1 entries
  - region "Notifications alt+T"
```