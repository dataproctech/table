Using the INVOICE table structure shown in table on image, do the following:

a. Write the relational schema, draw its dependency diagram, and identify all dependencies, including all partial and transitive dependencies. You can assume that the table does not contain repeating groups and that an invoice number references more than one product. (Hint: This table uses a composite primary key.)

b. Remove all partial dependencies, write the relational schema, and draw the new dependency diagrams. Identify the normal forms for each table structure you created.

c. Remove all transitive dependencies, write the relational schema, and draw the new dependency diagrams. Also identify the normal forms for each table structure you created.

d. Draw the Crow’s Foot ERD.

Note:

You can assume that any given product is supplied by a single vendor, but a vendor can supply many products. Therefore, it is proper to conclude that the following dependency exists:

PROD_NUM --> PROD_LABEL, PROD_PRICE, VEND_CODE, VEND_NAME

(Hint: Your actions should produce three dependency diagrams.)
