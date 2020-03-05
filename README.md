# abapGIT-tests-pcedit
abapGit Test with Files edited on PC

Reproduce:

1) Create online repo and pull

2) Switch repo to offline

3) Import abapGIT-tests-pcedit-master.zip into repo

ZIP contains with files edited on PC:

/src/zcl_test_class_pc_format.clas.abap and /src/zcl_test_class_pc_format.clas.xml where edited on PC 
-> crlf instead of lf 
-> no BOM in xml

4) abapgit shows diffs although files are logically the same
