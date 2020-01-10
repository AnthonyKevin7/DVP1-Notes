## DBS

Notes for DBS.

## Comparisons

* =
* !+ or <>
* <
* >
* <=
* >=
* like
* In
* between


### Select Statements
SELECT firstname, lastname, dob  
FROM users;  
WHERE firstname = 'John';

<!--

% = Wildcard. Ball park of statement entered

-->

### % Wildcard

WHERE lastname like '%ate';

<!--
Instance with multiple comparisons
-->

WHERE lastname = 'Smith' OR lastname = 'Jones' OR lastname = 'Senate';

### Aliasing
Alternative name for a column

SELECT userid, firstname AS fn, lastname AS ln  
FROM users;

## SQL Functions

* User Defined
* Pre-rendered

Aggregate and Scaler Functions

Aggregate = Sum of column data