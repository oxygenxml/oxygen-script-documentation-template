# Oxygen Script - Documentation Template
This project provides you with a template that uses <i>Oxygen Scripting</i> to generate HTML documentation for your schema files from a GitHub repository.
For the moment, it can only work with XSD, XSL and WSDL files.

To get things ready, follow these steps:
1. Create a new GitHub project using this template. This allows you to easily create a new repository without copying and pasting the content, and with no history or reference to this repository.
   All you have to do is click the <kbd>Use this template</kbd> button. Make sure to check <i>Include all branches</i> option.
2. Get an Oxygen Scripting license key from https://www.oxygenxml.com/xml_scripting/pricing.html (you can also request a [trial](https://www.oxygenxml.com/xml_scripting/register.html)). Add it as a secret to your repository (Settings &#8594; Secrets and variables &#8594; Actions &#8594; New repository secret), and name it "SCRIPTING_LICENSE_KEY".

Now, as the setup should be ready, you can add the schema files that you want to document to the <i>schemas</i> directory.
Feel free to use or remove the sample files provided with this template. To run the documentation script, follow these steps:
- In your GitHub repository, click on <b>Actions</b> tab.
- Select <b>Run Documentation Script</b> from the left panel.
- Click the <kbd>Run workflow</kbd> button in the right side.
- Type the name of the schema to document (e.g. personal.xsd).
- Click <b>Run workflow</b>.

📝 The generated documentation files will be deployed to <i>gh-pages</i> branch. Make sure the workflow has read/write permissions (Settings &#8594; Actions &#8594; General &#8594; Workflow permissions). Otherwise, you may not be able to deploy your documentation.

The main documentation file generated using Oxygen Scripting should be available here:
https://{userid}.github.io/{reponame}/{schemaName}.html

The main documentation file generated from <i>personal.xsd</i> file from <b>oxygenxml</b> repository is available here:
https://oxygenxml.github.io/oxygen-script-documentation-template/personal.html
