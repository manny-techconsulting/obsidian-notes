***Normalization*** is the process of minimizing ***redundancy*** from a relation or set of relations. 
Redundancy in relation may cause insertion, deletion, and update anomalies. 
So, it helps to minimize the redundancy in relations. 
***Normal forms*** are used to eliminate or reduce redundancy in database tables.

## 0NF or Unnormalized Form

## 1st Normal Form

This is the most basic level of normalization. 
In 1NF, each table cell should contain only a single value, and each column should have a unique name. 
The first normal form helps to eliminate duplicate data and simplify queries.

First Normal Form (1NF) does not eliminate redundancy, but rather, it’s that it eliminates repeating groups. 
Instead of having multiple columns of the same kind of data in a record, (0NF or Unnormalized form) you remove the repeated information into a separate relation and represent them as rows. 
This is what constitutes 1NF.

According to Date's definition, a table is in first normal form if and only if it is "[isomorphic](https://en.wikipedia.org/wiki/Isomorphism "Isomorphism") to some relation", which means, specifically, that it satisfies the following five conditions.

> 1. There's no top-to-bottom ordering to the rows.
> 2. There's no left-to-right ordering to the columns.
> 3. There are no duplicate rows.
> 4. Every row-and-column intersection contains exactly one value from the applicable domain (and nothing else).
> 5. All columns are regular [i.e. rows have no hidden components such as row IDs, object IDs, or hidden timestamps
## 2nd Normal form

The second Normal Form (2NF) is based on the concept of fully functional dependency. 

The second Normal Form applies to relations with composite keys, that is, relations with a primary key composed of two or more attributes. 
A relation with a single-attribute primary key is automatically in at least 2NF. A relation that is not in 2NF may suffer from the update anomalies. To be in the second normal form, a relation must be in the first normal form and the relation must not contain any partial dependency.

A relation is in 2NF if it has No Partial Dependency, i.e., no non-prime attribute (attributes that are not part of any candidate key) is dependent on any proper subset of any candidate key of the table. In other words,



## 3rd Normal Form

## 4th Normal Form

## 5th Normal Form

## Boyce Codd Normal Form
