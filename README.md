# Individual Assignment II: Oracle Pluggable Databases (PDB) Management

**Student Name:** NIYONGABO ILISA Ercine  
**Student ID:** 29864  
**Course:** Database Development with PL/SQL (INSY 8311)  
**Instructor:** Eric Maniraguha  
**Submission Date:** February 16, 2026

The assignment requires students to demonstrate their understanding of Oracle Multitenant Architecture through practical work which includes Pluggable Database (PDB) creation and operational control. The three technical tasks I completed required me to create a PDB with a user account and to establish and terminate a temporary PDB and to use the Oracle Enterprise Manager (OEM) dashboard. I completed all tasks through my personal Oracle setup which I operated on my home computer.

## Oracle Environment Used
- **Oracle Version:** Oracle Database 21c Express Edition (XE)  
- **Operating System:** Windows  
- **Tools Used:** SQL*Plus, Oracle Enterprise Manager (OEM)  
- **Setup:** Default CDB$ROOT container and PDBSEED

## Explanation of Each Task

### Task 1: Create a New Pluggable Database The database will use the name er_pdb_29864 The database will use the username ercine_plsqlauca_29864 The database will use the password auca123

The following SQL commands were run which can be seen in the evidence screenshots

- Connect as SYSDBA 
- Set Container Session
- Open Pluggable Database (Success)
- Open Pluggable Database (Error) 

The evidence requires the following screenshot to be inserted The database will use the username ercine_plsqlauca_29864 The database will use the password auca123

The following SQL commands were run which can be seen in the evidence screenshots

- Connect as SYSDBA
- Set Container Session
- Open Pluggable Database (Success)
- Open Pluggable Database (Error)

  <img width="308" height="53" alt="connect as sysdba" src="https://github.com/user-attachments/assets/15f31a66-c253-4fee-be82-4b91a4c5b855" />
  <img width="490" height="111" alt="session alt" src="https://github.com/user-attachments/assets/927d90e9-fa9c-47a2-ae17-a92376358daf" />
  <img width="457" height="118" alt="open pluggable db" src="https://github.com/user-attachments/assets/9764cce8-d3a6-42dc-8477-e4d8cce542ee" />
  <img width="491" height="163" alt="error" src="https://github.com/user-attachments/assets/6025c309-6b9c-4e51-bbda-a9b423176c1d" />


## Task 2: Create and Delete a PDB 

Temporary PDB Name: er_to_delete_pdb_29864 

Executed SQL Commands (Screenshots as Proof): 

- Show Container Name 
- Open Pluggable Database (first)
- Open Pluggable Database (Second) 
- Close Pluggable Database
- Grant privilege 
- Drop Pluggable Database
- Create user
- Create Pluggable Database (To Delete)
  
   <img width="550" height="162" alt="show con name" src="https://github.com/user-attachments/assets/2c32c268-b58d-4812-888d-191fd8046f41" />
   <img width="566" height="86" alt="open pluggable db step1" src="https://github.com/user-attachments/assets/b7f78dcd-9804-419d-aa65-31f5cd1e9c2a" />
   <img width="646" height="117" alt="open pluggable database" src="https://github.com/user-attachments/assets/eaaccb1f-8f83-4b46-8d10-5ff5a5959875" />
   <img width="660" height="114" alt="close pluggable database" src="https://github.com/user-attachments/assets/b3adec96-d8c1-4320-89c9-7f4bde3c86f6" />
   <img width="564" height="120" alt="grant priveledges" src="https://github.com/user-attachments/assets/4844b32e-5683-49fd-b4db-d30e9b7b03eb" />
   <img width="651" height="119" alt="drop db" src="https://github.com/user-attachments/assets/bd42e894-fdae-4571-b84c-d44c9b4c4ae6" />
   <img width="570" height="121" alt="create user" src="https://github.com/user-attachments/assets/cf5111c9-f887-494e-b11a-ad63ee2e8a31" />
   <img width="581" height="187" alt="create pluggable db to delete" src="https://github.com/user-attachments/assets/a18e5a97-ec1a-41f6-9720-4f3aa866c0fe" />


## Task 3: Oracle Enterprise Manager (OEM) 

I accessed Oracle Enterprise Manager to check the environment and tasks that were done. 

Proof: 

   <img width="1908" height="885" alt="OEM dashboard (1)" src="https://github.com/user-attachments/assets/b3ec2da1-b975-498b-9675-8caa072c01ab" />

### Task 4: Documentation and Reporting
The professional report is presented through this document which uses the README.md format and shows the repository as accessible to all users. 

## Challenges Faced and How They Were Solved
- The system returned **ORA-01031: insufficient privileges** when users attempted to access the PDB through their non-SYSDBA accounts after they switched container. The system admin first established a SYSDBA connection before proceeding to open or alter PDB content.

## Integrity Statement
I, Ercine (Student ID: 29864), confirm that this is my own individual work. I did not copy any commands or screenshots or code from my classmates. AI tools were not used to produce the SQL commands or solutions. I captured all screenshots during my personal execution of the tasks.

Repository Name: oracle_pdb_ass_II_29864_NIYONGABO  
Visibility: PUBLIC  

**Repository Link:** https://github.com/ilisaercine/oracle_pdb_ass_II_29864_NIYONGABO/tree/main
**PDB Name Created:** er_pdb_29864  
**Issues Encountered:** Yes (minor privilege error – resolved as explained above)




   








  

  
