
# Flexix\ConfigurationBundle installation description

>by Mariusz Piela <mariusz.piela@tmsolution.pl>


---



### Installation

To install the bundle, add: 

```
//composer require

"flexix/configurationBundle": "dev-master"
```

to your project's `composer.json` file. Later, enable your bundle in the app's kernel:

```
<?php
// app/AppKernel.php

public function registerBundles()
{
    $bundles = array(
        // ...
        new Flexix\ConfigurationBundle\FlexixConfigurationBundle()
    );
}
