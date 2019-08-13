Forked from vim-python/python syntax with a few changes:

* `raise`,`assert` moved from pythonStatement to pythonException
* `=` moved from pythonOperator to pythonStatement
* `'single quote strings'` moved from pythonString to the new pythonSymbol, which extends Label
* `in` is in pythonOperator, except the `in` from `for .. in`, which is in pythonRepeat
* `from` will now correctly match pythonImport
* `this` has been added to pythonClass
