# ANSI/SPARC

The **ANSI-SPARC Architecture** is a standard framework for designing a database management system (DBMS). It was proposed by the Standards Planning and Requirements Committee (SPARC) of the American National Standards Institute (ANSI).

Its central idea is to separate what users see of the data from how the data is stored. To achieve this, it divides the database
into three levels, each described by its own schema.

## External level (User View)
This is the level closest to the users. Each user or application sees only the part of the database relevant to them, presented in a form that suits their needs. 
For example, a student may see only their **grades**, while an administrator sees **full enrollment records**.

## Conceptual level (Logical View)
This level describes the database as a whole: what data is stored, how it is organized, and how the pieces relate to each other. It hides all physical storage details and serves as the common structure behind every user view.

## Internal level (Physical View)
This is the level closest to the hardware. It describes how the data is physically stored, including file structures, indexes, and storage methods.

