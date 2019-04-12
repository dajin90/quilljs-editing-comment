# Quill Inline Comment
Module extension for [Quill.js](https://github.com/quilljs/quill) that handles inline comment like medium.

#### This module is still in active development
This module is contained add comment and update comment functions.
## Usage
### Webpack/ES6

```javascript
          var toolbarOptions = {
            container: [
              ['bold', 'italic', 'underline', 'strike'],
              ['blockquote', 'code-block'],
              [{ 'header': 1 }, { 'header': 2 }],
              [{ 'list': 'ordered' }, { 'list': 'bullet' }],
              [{ 'script': 'sub' }, { 'script': 'super' }],
              [{ 'indent': '-1' }, { 'indent': '+1' }],
              [{ 'direction': 'rtl' }],
              [{ 'header': [1, 2, 3, 4, 5, 6, false] }],
              [{ 'color': [] }, { 'background': [] }],
              [{ 'font': [] }],
              [{ 'align': [] }],
              ['clean'],
              ['link', 'image', 'video'],
              ['comment'],
              ],
              comment: [{
                  create_id : 2334,
                  create_name : "John Doe",
                  create_email : "john@doe.com",
                  comment: "a comment",
                  suggestion : "interesting topic", 
                  privilege : 'author'
              }
            ],
          }
```

## Contributing

Please check out our [contributing guidelines](CONTRIBUTING.md).
