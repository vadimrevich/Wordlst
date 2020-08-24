WORDLST
=======

����� �������� ��� ��������� ������� � ��������� �������� ������ � �������������.

��������! ������������ ������ ��� �������� �����, ��������, �������������� ����������� ������� �������. �������� ����� ��������� ������������ �������.

��������
--------

������ ����� �������� �������� ����� ������� ��� ��������� ������� � ��������� ��������, ���������������� ��� �������������� �������� ���������. ��� ���������� ������� ��������� ���� ��������� ������ ������� �� ��� top500. ��� ������� ������������ ����� �������� � ������ ���� �������.

������� �������������� ��-��������� � ������� %PUB1%\WORDLIST � ������������� �� ���������, ���  ��������� �� �������.

������ ��������� ����� ���������:

/* ��������� 15.02.2009
* Docs � ������� � ������������� (�� ���������)
* DRAFT � ������� � ���������� � �������� ���������
(����������. ��� ��� �������� � ������ ��� �������������. �� ������ ������� �� ����� ����������� ��������.) */
* PASSWD � � ����� ������� ������ � ��������� OEM 866 (������� MS-DOS). �������� �������� ��� �������� �������� ������� �� ��������� ������ DOS � Windows.
* UTF � � ����� ������� �� �� ������ � ��������� UTF �������� ��� ������� ������� � ���������� � ����������� ����������� Linux � Windows.
* WIN � � ����� ������� ������ � ��������� Windows ANSI 1251 (������� Windows). �������� ��� ������� ������� � ���������� ���������� Windows � ����������� �����������
* LOGIN � ����� �� ������� ��� ������� ������� � ������������� Windows � ����������. �������� ���� ������ ������������� ��������� ������������ ��������. ��������� OEM 866 ������������ ��� ���������.

�������������
-------------

��� ������� ������� ������� ������� ������ ���� �� ������� ��� ���������.

�����������
-----------

��� ��������� �������� ��������� ���� Wordlst-Install.exe � �������� ���������� � �������. ��������� ������������� ���������� ������������� ��� �������� ��������.

������ ������������
-------------------

1. ���������� ����� Inno Setup.
2. ������� ������� �������� ���������������� ���� Wordlst-Install.iss � ��������.
3. ��������� ���� ���� ��� ���� ����� (��. ������������ � Inno Setup).
4. ������� ������ Build � �������� �����������.

WORDLST
=======

Packet of dictionaries for brute of passwords to different services together with an installer.

Attention! Use only for the legal purposes, for example, for recovery of own forgotten passwords. Brute force of someone else's accounts is pursued by the law.

DESCRIPTION
--------

This packet contains the most general dictionaries for brute of passwords to different services, optimized for a Russian-speaking segment of the Internet. For reduction of the dictionary base extent only dictionaries from top500 bases are provided. If users are desired they can add the dictionaries to assembly.

Dictionaries are installed by default in the directory %PUB1%\WORDLIST and are located according to subfolders as it is given in the server.

Catalog of folders tree is following:

/* It is added 15.02.2009
* Docs is the catalog with documentation (not dictionaries)
* DRAFT is the catalog with reference and working dictionaries
(NOTE. These two catalogs is only for developers. You can remove them after installation of dictionaries.) */
* PASSWD � in the folder are collected passwords in OEM 866 encoding (the Russian of MS-DOS). Is ideal for programs of a password search from the command line of DOS and Windows.
* UTF � in the folder are brought together the same passwords in UTF encoding/ They are suitable for � passwords search in programs with the graphic interface of Linux and Windows.
* WIN � in the folder are brought together passwords in Windows ANSI 1251 encoding (the Russian Windows). They are suitable for a password search in outdated programs of Windows with the graphic interface
* LOGIN � the folder with words for a logins selection for Russian-language Windows and programs. Suffixes of these files correspond to encoding of the used characters. The OEM 866 encoding is presented without suffixes.

USE
---

Specify a full path to the dictionary for brute force at searching of the forgotten passwords.

INSTALLATION
------------

For installation of dictionaries start the Wordlst-Install.exe file and follow hints in dialog. The program installs the built-in uninstaller for removal of a product.

ASSEMBLY OF THE INSTALLER
-------------------------

1. Install Inno Setup packet.
2. Double click on the demonstration Wordlst-Install.iss file to open it in a cover.
3. Correct this file under the needs (see documentation of Inno Setup).
4. Click Build and create an installer.
