---
version: 1
title: Demo Support
url: https://www.spprt.test/
company: spprt.io
imprint: https://www.spprt.io/imprint
privacy: https://www.spprt.io/privacy
terms: https://www.spprt.io/terms
form:
    title: Get help with Demo
    text: What you want to say, to us.
    fields:
        name:
            label: Name
            type: text
            placeholder: Your name
            required: true
        email:
            label: Email
            type: email
            placeholder: Your email address
            required: true
        categories:
            label: Category
            type: select
            required: true
            options:
                first_name:
                    name: Hello3
                    labels: 
                        - test
                    assignees:
                        - dschniepp 
                last_name:
                    name: 1Hello2
                    labels:
                        - test
                    assignees:
                        - dschniepp 
        title:
            label: Subject
            type: text
            placeholder: Your subject
            required: true
        body:
            label: How can we help?
            type: textarea
            placeholder: Your request
            required: true
---
# Support

## Secondary Header

### Third level header

Here you can add support information.

How does it look on GitHub? [GitHub Repo](https://github.com/spprt-io/demo/issues)
