## The Google File System
**Developers:** Anand Balan and Nandita Koppisetty

##### Objective:
The objective of this project is to implement a miniature version of the Google File System with ability to create a file, read a file and append to a file as discussed in the paper:  
Sanjay Ghemawat, Howard Gobioff, and Shun-Tak Leung. 2003. The Google file system. SIGOPS Oper. Syst. Rev. 37, 5 (October 2003), 29-43. DOI=http://dx.doi.org/10.1145/1165389.945450

##### HOW TO RUN THE PROGRAM?
1. Open 8 terminals each connected to dc machines 01 to 08.
2. Go the bin folder present in the project root directory.
3. Run the following command:
	For server:
		java FileServerStarter <server_id> <path_to_server_config_file> <path_to_metaserver_config_file>
	For meta server:
		java MetaServerStarter <server_id> <path_to_metaserver_config_file> <path_to_server_config_file>
	For clients:
		java ClientStarter <server_id> <path_to_client_config_file> <path_to_server_config_file> <path_to_metaserver_config_file>
4. Run the meta server first, then file servers and then the clients, in that order.
5. Follow the instructions in the client terminal.