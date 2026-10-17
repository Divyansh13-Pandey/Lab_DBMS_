# DBMS Practical Experiments — MySQL

Contains Experiments 1–10 in separate `.sql` files. Each file includes an Aim, Source Code, and a blank Output section. `ER_Diagram.png` is included for Experiment 1.

## Run instructions
1. Use MySQL 8.0+ and MySQL Workbench.
2. Run each file in a test environment. Experiments 3–6 share `EmployeeDB`; other experiments create separate databases.
3. Experiment 2 includes commented invalid INSERT statements. Uncomment and run one at a time to observe integrity errors.
4. Experiment 8's concurrency section is commented; run the indicated steps in two separate MySQL sessions.
5. Experiments 9 and 10 use generated datasets (5,000 and 10,000 rows). Compare `EXPLAIN` results before and after indexes.
6. The Output sections are intentionally blank so execution results/screenshots can be added.

Note: Query plans and timings vary by MySQL version and machine. Review scripts before executing.
