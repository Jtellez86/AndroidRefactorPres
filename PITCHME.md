---

# Android View Refactor

---

## Disclaimer: 

There is no single perfect solution to how you build your views. Sorry.

---

## Goals of the refactor:

* Consistency
* Simplicity
* Testability
* Bonus: AppCompat

---
## State of views as of 12/7

---
### History
* Simple Layout
* No databinding
* Everything in Activity
![History Activity](./screenshots/history/historyActivityBefore.png)
---
### Active Rescue List
* Uses a fragment
* Uses databinding in Fragment

ActiveRescueActivity       |  ActiveRescueListFragment
:-------------------------:|:-------------------------:
![](./screenshots/activeRescue/activeRescueActivityBefore.png) | ![](./screenshots/activeRescue/activeRescueFragment.png)
  

---
## Single Fragment Activities
