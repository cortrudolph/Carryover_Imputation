# Carryover_Imputation

A set of R scripts that simulates within-person longitudinal data (*N* can be
specified), removes X% cases at random (MAR), and then applies various missing
data remediation procedures, including carryover imputation (i.e., last
observation carried forward), and multiple imputations via the `PAN` algorithm.

Useful for testing/demonstrating the viability of different means of remediating
missing data in complex (i.e., within-person, longitudinal) data.
