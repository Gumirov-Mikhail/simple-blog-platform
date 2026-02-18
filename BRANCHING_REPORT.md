# Branching Report

## Merge Statistics
- Total number of merges: [5]
- Fast-forward merges: [1]
- 3-way merges: [4]
- Merges with conflicts: [2]

## Branch History
[Вставьте вывод команды git log --graph --oneline --all]
```
```
*   bab0833 (HEAD -> master, origin/master) Merge branch 'documentation'
|\
| * 7f983d7 (documentation) improve README
|/
*   5e85ae5 Merge feature/header-update with conflict resolution
|\
| * 787c40e Update header to v2.0
* | 8e7e196 Customize blog title
|/
*   2728bef Merge branch 'feature/design'
|\
| * dc0f6f0 Improve design and add navigation
* |   f3f60bb Merge branch 'feature/comments'
|\ \
| |/
|/|
| * b72853c Add comments section
|/
* b506cbf Add posts page and functionality
* 2eefea6 Initial project setup
```
```

## Lessons Learned
[Опишите 2-3 предложениями, что вы узнали о ветвлении и слиянии]
Конфликты неизбежны и не стоит их бояться, есть различные флоу разработки, которые подразумевают ветвление и слияние. Очень удобно конфликты решать с помощью различных mergetools
