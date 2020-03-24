# ProcessWire Snippets

Snippets for rapid PHP Development with the ProcessWire CMS/CMF

## Features

**Please see section `Contributing` how you can add features!**

I'm using the `Intelephense` extension for Code Intellisense in PHP in the examples.

### pw: Add ProcessWire Namespace

![img](https://i.imgur.com/SVQEyHP.gif)

### pwmod: Get ProcessWire Module

![img](https://i.imgur.com/oKSjntZ.gif)

### pwmodule: PW Module Boilerplate

![img](https://i.imgur.com/hQ9m9mQ.gif)

### pwinputfield: Add Inputfield Boilerplate

![img](https://i.imgur.com/vjpI48U.gif)

### pwfieldtype: Add Fieltype Boilerplate

![img](https://i.imgur.com/g1iMIbz.gif)

### pwprocessmodule: Add ProcessModule Boilerplate

![img](https://i.imgur.com/jPOccIx.gif)

### pwexecuteFoo

![img](https://i.imgur.com/hQ5rjUa.gif)

### pwModuleConfigClass: Add PW Module Config Class Boilerplate

![img](https://i.imgur.com/koIOKVZ.gif)

### pwSqlQuery: Query the database via SQL

![img](https://i.imgur.com/2E6NoZ6.gif)

![img](https://i.imgur.com/e0C0fdv.png)

### pwex and pwex404: Throw WireExceptions

![img](https://i.imgur.com/h81Noe3.gif)

### pwhook and pwHookInline: Attaching hooks

![img](https://i.imgur.com/JpjLTc7.gif)

### pwResetAdmin

![img](https://i.imgur.com/8BylgUT.gif)

## Contributing

**First, create your snippet in your users folder to test it! [See docs](https://code.visualstudio.com/docs/editor/userdefinedsnippets)**

When it works, go to your VSCode Extensions folder
```
cd C:\Users\foo\.vscode\extensions\
```

*If you have PWSnippets extension installed, uninstall it (or delete the folder now)!*

Fork this Repo into your Github account and clone it into the extensions folder:
```
git clone git@github.com:yourGitAccount/pwsnippets.git
```

Create a test-file and check that the extension works:

```
cd pwsnippets
touch test.php
```

Open the extension's folder in VSCode:

![img](https://i.imgur.com/5GIQQOY.png)

Now open `test.php` and type `pw`. The `PW Namespace` snippet should pop up:

![img](https://i.imgur.com/sHMrP9v.png)

Now open `snippets/php.json` and add this test-snippet to your json:

```
"pw-test": {
  "prefix": "pwtest",
  "body": [
    "PWTest working!"
  ],
  "description": "Test Snippet"
}
```

*Make sure to separate all snippet objects by commas except the last one (it needs to be valid JSON syntax)!*

**Reload the window!**

Go to `test.php` and type `pwtest`:

![img](https://i.imgur.com/HTwxSRs.png)

Now add your own snippets. When done create a Pull Request so that I can update the VSCode Extension.

Thank you :)
