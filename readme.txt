-------------
SharedLibrary
-------------


- Contains classes with functionality useful for more than one program. Usually, these classes are less general than what is provided by Java libraries. The objective is to provide narrower, practical code for common scenarios. For example:

	# Logging methods to ease the use of Java Logger, to be used as a substitute of System.out and System.err.
	# Methods to ease the use of Java Preferences and provide simple backup to Properties files of some parameters.
	# Methods for basic manipulation of Files (reading, writing) without having to deal with exceptions.