USAGE:- 
git clone https://github.com/karanbir-singh001/chattr
gcc chattr.c -o chattr
chmod +x chattr
./chattr file_name 16 ( 16 IS TO ADD ATTRIBUTES TO MAKE FILE UNWRITABLE AND UNDELETABLE )
./chattr file_name 0  ( 0 IS TO REMOVE ATTRIBUTES )
