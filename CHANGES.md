
## 0.5.10:

   * added listen method for easy launching of services
   * added client method for easy http access of services

## 0.5.9: 

   * add export feature for plugins
   * seneca.depends - check plugin dependencies registered
   * API CHANGE: seneca.fail throws if no callback      
   * API CHANGE: seneca.http, mapping spec, data:true means place req.body into 'data' arg
   * API CHANGE: no async inside module def init:_plugin_ used instead for async init
   * API CHANGE: seneca.service replaced by seneca.export('web')

## 0.5.8: 2013-05-29

   * Entities get an inspect() function for util.inspect
   * Entity.toString prints nicer object values
   * SENECA_LOG environment variable can be used instead of --seneca.log command line arg
   * Seneca instance given to plugin init function includes a context object with reference to calling code module
   * Logging output slightly prettier
   * Config plugin looks for seneca.config.js in calling code folder
   * Config plugin supports environments


## 0.5.3: 2013-03-26

   * seneca.util.deepextend supports boxed types, thanks Mircea!


   