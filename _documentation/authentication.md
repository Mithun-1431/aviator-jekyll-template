---
title: Authentication
position_number: 9
parameters:
  - name: Rhaan
    content: Rihaan's Content
content_markdown: >-
  You need to be authenticated for all API requests. Adding a line-1 by Mithun
  Prabhakara. Adding-line-2. Adding-line-3. Adding-line-4. Line created after
  creating the branch "Mithun-Created-Branch" in GitHub.


  **This line and following table is added after synching the file to GitHub.**


  | **Rihaan** | **Chinmay** |

  | Rihaan table Content | Chinmay Table Content |

  |  |  |


  You can generate an API key in your developer dashboard.


  Add the API key to all requests as a GET parameter.


  Nothing will work unless you include this API key

  {: .error}
left_code_blocks:
  - code_block: Shruthi's Code Block
    title: Shruthi
    language: java
right_code_blocks:
  - code_block: |2-
       $.get("http://api.myapp.com/books/", { "token": "YOUR_APP_KEY"}, function(data) {
         alert(data);
       });
    title: JQuery
    language: javascript
  - code_block: ' curl http://api.myapp.com/books?token=YOUR_APP_KEY'
    title: Curl
    language: bash
---
