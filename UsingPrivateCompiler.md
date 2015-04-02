Using LaTeX Lab with a private CLSI compiler.

### Setting up your own CLSI server ###

Follow the instructions on the CLSI project's <a href='http://code.google.com/p/common-latex-service-interface/wiki/InstallAndConfig'>Installation and Configuration</a> page to bring up a CLSI instance.

### Configuring LaTeX Lab ###
You can configure LaTeX Lab to use a custom CLSI instance by specifying the necessary values in the Compiler -> Settings dialog.

For example, if your CLSI instance's root url is `http://myclsi.org/clsi/`, then you would enter the following compiler settings in LaTeX Lab:
  * Select _Use a third party CLSI provider_.
  * **Service URL**: `http://myclsi.org/service.php`
  * **Service Token**: `any alphanumeric 10 character value will do`
  * **Service Output Path**: `http://myclsi.org/out/<id>/`
  * **Compiler Name**: `latex`