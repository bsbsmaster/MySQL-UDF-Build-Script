# MySQL-UDF-Build-Script
This Bash script automates the process of building and installing a MySQL User Defined Function (UDF) library called lib_mysqludf_sys. UDFs allow users to extend MySQL's functionality by adding custom functions written in C or C++.
./build_udf.sh {architecture} {operating_system} {plugin_directory}
exmplie 
## generate the dll
bash mysql-udf-build.sh 64 win .
