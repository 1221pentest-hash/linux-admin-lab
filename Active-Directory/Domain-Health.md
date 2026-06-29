# Domain Health Assessment

## Objective

Perform a baseline assessment of the Active Directory environment before implementing infrastructure improvements.

---

## Environment

| Setting                 | Value                   |
| ----------------------- | ----------------------- |
| Domain Name             | LORO.local              |
| Domain Controller       | DC-01                   |
| Forest Functional Level | Windows Server 2016     |
| Global Catalog          | DC-01                   |
| Site                    | Default-First-Site-Name |

---

## Assessment Performed

The following diagnostic commands were executed:

* dcdiag
* Get-ADDomain
* Get-ADForest
* netdom query fsmo

---

## Results

The Active Directory environment is operational.

The forest contains a single domain:

* LORO.local

The forest functional level is Windows Server 2016.

DC-01 hosts the Global Catalog and FSMO roles for the environment.

No critical issues were identified during the initial assessment.

---

## Conclusion

The environment is suitable for expansion and will be used as the foundation for the Enterprise System Administration Lab.
