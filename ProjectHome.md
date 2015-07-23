Library which contains classes with functionality useful for more than one program. Usually, these classes are less general than what is provided by Java libraries. The objective is to provide narrower (when compared with the Java APIs), practical code for common scenarios. For example:

  * Logging methods to ease the use of Java Logger, to be used as a substitute of System.out and System.err.
  * Methods to ease the use of Java Preferences and provide simple backup to Properties files of some parameters.
  * Methods for basic manipulation of Files (reading, writing) without having to deal with exceptions.

"Shared Library.jar" is the main release. "Shared Library Rxtx" is a small, separate set of methods which uses the [htt://users.frii.com/jarvi/rxtx/ RXTX Comm] library for communication using serial ports.

# Updates #

## Shared Library 1.1 (2010-02-10) ##

Added download for "Shared Library 1.1".

Changes:

  * Changed method append() in class IoUtils. Subsequent append operations to the same file are not reported to the logger, until another different file is appended.
  * Added the following methods to ParseUtils:
    * String removeSuffix(String text, String separator)
    * String toHexString(long decimalLong, int stringSize)
    * int indexOfFirstWhiteSpace(String string)

  * Added class BitUtils.
  * Added Class DataStructures.PushingQueue.