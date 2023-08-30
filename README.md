# Oracle-SQL-for-Claim-Made-Policies
Oracle Database SQL code that aggregates claim-made policies based on specific criteria. In this example, we'll calculate the total written premium (WRTN_PREM_AMT_ITD) and the count of distinct policyholders (POLICYHOLDER_ID) for each category of the claim-made policies. We'll group the results by the policy category determined by the POLICY_FORM_CODE and the time since the inception of the coverage.

ClaimMadePolicyTable should be replaced with the actual name of the table where your claim-made policy data is stored. 
This code calculates the aggregate total written premium and policyholder count for each policy category and time since inception of coverage. 
The results are grouped by policy category and ordered accordingly.
