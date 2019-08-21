# Versions of data dictionaries
We define here in what versions of the data dictionaries contains which tables.

Filenames contain the minor versions as well. The tablenames are more stable and contain only the major version.

*Example filenames*
* 1_1_non_repeated_measures.xlsx
* 1_1_monthly_repeated_measures.xlsx
* 1_1_yearly_repeated_measures.xlsx

*Table names*
* 1_non_repeated_measures
* 1_monthly_repeated_measures
* 1_yearly_repeated_measuress

## 1.1
Additional variables from WP3 and changes in the lifecycle variables.

### Content

**LifeCycle variables**
* art --> variable_id changed from **art** to **mar**

  >**be adviced**: all harmonisations of all cohorts need te upload this variable again with the new name
* preg_plan --> values updated from ( 0 = No (not planned) / 1 = Yes (Planned, partly planned)) to ( 1 = Yes (Planned, partly planned) / 2 = No (not planned))

**EUSILC variables (task 3.1.1)**

| Variable               | Description                                                                  | Datatype    |
| ---------------------- | ---------------------------------------------------------------------------- | ----------- |
| eusilc_income          | Log-equivalised total disposable household income predicted                  | continuous  |
| eusilc_income_quintiles| Quintiles of the log-equivalised total disposable household income predicted | categorical |

**Migration variables (task 3.1.x)** 

| Variable     | Description                      | Datatype    |
| ------------ | -------------------------------- | ----------- |
| abroad_child | Child's born abroad	          | binary      |
| abroad_mo	   | Mother's born abroad	          | binary      |
| abroad_fa	   | Father's born abroad	          | binary      |
| miggen_child | Child's migrant status	          | categorical |
| region_mo	   | Mother’s world region of birth   | categorical |
| region_fa	   | Father’s world region of birth	  | categorical |
| reledu_mo	   | Mother’s educational selectivity | decimal     |
| reledu_fa    | Father’s educational selectivity | decimal     |

### Tables
- 1_non_repeated_measures

## 1.0
### Content
- Includes all lifecycle variables harmonised by all cohorts

### Tables
- 1_non_repeated_measures
- 1_monthly_repeated_measures
- 1_yearly_repeated_measures