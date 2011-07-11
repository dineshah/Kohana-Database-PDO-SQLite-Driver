
Sample Database Configuration for using PDO SQLite driver

~~~
return array
(
	'sqlite' => array(
		'type'			=> 'pdo_sqlite',	// Make sure to use this name as type
		'connection'	=> array(
			'dsn'			=> 'sqlite:/path/to/database.sqlite',
			'persistent'	=> FALSE,
		),
		'table_prefix'	=> '',
		'charset'		=> 'utf8',
		'caching'		=> FALSE,
		'profiling'		=> TRUE,
	),
);
~~~

