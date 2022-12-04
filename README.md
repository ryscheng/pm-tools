# pm-tools

A front-end web app and scripts for project management,
in the style of GitHub issues or Shortcut.

Instead of writing to a database, the application will write
to a local folder, which must follow the hierarchy
and file formats specified in
[pm-template](https://github.com/ryscheng/pm-template.git),
with the optional ability to commit/push/pull to a remote repository.

## Setup

First, make sure you have a local git repository that follows the format of
[pm-template](https://github.com/ryscheng/pm-template.git).

If you don't already have one, navigate to the
[pm-template](https://github.com/ryscheng/pm-template.git) repo,
fork the repository, and clone locally.

```
git clone git@github.com:MY_ORG/pm-template.git
```

Specify the local absolute path to this repo in the `PM_TEMPLATE_PATH`
environment variable.

```
export PM_TEMPLATE_PATH=/home/user/pm-template
```

### git setup (Optional)

If you want to push and pull to a remote git repository,
make sure your `.gitconfig` is properly set up.

## Usage

### Local hosting

Start the local development server

```bash
yarn install  # or `npm install`
yarn start    # or `npm start`
```

Then navigate to `http://localhost:3000` to start using.

