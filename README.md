----------------------------
Indirect Predicates for Geometric Constructions
----------------------------

by Marco Attene

Consiglio Nazionale delle Ricerche                                        
Istituto di Matematica Applicata e Tecnologie Informatiche                
Sezione di Genova                                                         
IMATI-GE / CNR                                                            

This software implements fast and guaranteeed floating point geometric predicates,
including novel indirect predicates as described in the following article:

M. Attene. Indirect Predicates for Geometric Constructions. In Elsevier Computer-Aided Design (2020, to appear).

-------------------
Citation policy
--------------------
You are free to use this software according to the licensing terms specified at the end of this document.
If you use it for research purposes and produce publications, please cite the following paper 
that describes the underlying theory:

> M. Attene. Indirect Predicates for Geometric Constructions. In Elsevier Computer-Aided Design (2020, to appear).

-------------------
System Requirements
--------------------

The software has been tested on 64 bit PCs running:
 - Microsoft Windows OS with MSVC
 - Linux with standard gcc/g++ development environment
 - Mac OSX. Unfortunately CLANG does not support direct access to the floating point environment.
   The only way to use this software with CLANG is to disable all optimizations (-O0).


---------------------
Copyright and license
---------------------

Indirect_Predicates
Authors: Marco Attene                                                    

Copyright(C) 2019: IMATI-GE / CNR                                        

IMATI-GE / CNR is Consiglio Nazionale delle Ricerche                     
Istituto di Matematica Applicata e Tecnologie Informatiche               
Genova (Italy)                                                           

Indirect_Predicates is free software; you can redistribute it and/or modify     
it under the terms of the GNU Lesser General Public License as published 
by the Free Software Foundation; either version 3 of the License, or (at 
your option) any later version.                                          

Indirect_Predicates is distributed in the hope that it will be useful, but      
WITHOUT ANY WARRANTY; without even the implied warranty of               
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU Lesser 
General Public License for more details.                                 

You should have received a copy of the GNU Lesser General Public License 
along with the Indirect_Predicates. If not, see http://www.gnu.org/licenses/.
