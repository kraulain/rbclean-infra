# rbclean-infra

__table of content__

- [local setup](#setup-repo-locally)
- [how to render the](#how-to-render-the-documentation)
- [contributing](#contributing)
- [API tags](#api-tags)

## setup repo locally

- Clone repo with
  
  ```bash
    git clone git@github.com:kraulain/rbclean-infra.git
  ```

- Navigate to project with from your terminal

  ```bash
    cd rbclean-infra
  ```

## How to render the documentation

<!-- - Install Redoc CLI with the command `npm i redoc-cli g` -->

- Start local server for the spec in watch mode

    ```bash
      npm run dev
    ```

- Create a deployable zero-dependency HTML file

- Generate the html with

    ```bash
      npm run build:html
    ```

## Contributing

- Branches should be name with `feature/<task>` format

- Writing commits
  - Commit messages should follow the for mat `#<issue_number> | <author_name> | <work_description>`

  - @example is `#1 | Kraulain | create empty repo`

  - The numbering is with respect to the issue number your are working on

- ### API tags

  - Auth
  - Users
  - Orders
  - Notifications
  - Reports

|

___

__Happy Coding 🚀__
