---
version: 1
helpDesk:
    title: Demo Support # Help Desk Title
    company: spprt.io # (optional) Company name
    logo: iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAIAAACQd1PeAAAADElEQVQImWNwNj8FAAIFAUXasrNKAAAAAElFTkSuQmCC # (optional) Base64 ecoded logo
    sidebar: # Sidebar navigation
    - title: Form # Section title
      link: /form # (optional)
      children: # (optional)
      - title: Fields
        link: /fields
    footer: | # Markdown
        Test footer
email:
    footer: | # Markdown
        spprt.io
form:
    text: | # Markdown
        What you want to say, to us.
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
