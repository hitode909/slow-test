```
% time prove t/  --state=slow,save
t/4.t .. ok
t/3.t .. ok
t/2.t .. ok
t/1.t .. ok
All tests successful.
Files=4, Tests=8, 10 wallclock secs ( 0.02 usr  0.01 sys +  0.06 cusr  0.01 csys =  0.10 CPU)
Result: PASS
prove t/ --state=slow,save  0.17s user 0.06s system 2% cpu 10.227 total
[hitode909@superfamilycomputer.local:~/co/slow-test]
% time prove t/  --state=slow,save -j2
t/3.t .. ok
t/4.t .. ok
t/1.t .. ok
t/2.t .. ok
All tests successful.
Files=4, Tests=8,  5 wallclock secs ( 0.03 usr  0.01 sys +  0.06 cusr  0.01 csys =  0.11 CPU)
Result: PASS
prove t/ --state=slow,save -j2  0.18s user 0.06s system 4% cpu 5.193 total
[hitode909@superfamilycomputer.local:~/co/slow-test]
% time prove t/  --state=slow,save -j3
t/2.t .. ok
t/3.t .. ok
t/1.t .. ok
t/4.t .. ok
All tests successful.
Files=4, Tests=8,  4 wallclock secs ( 0.03 usr  0.01 sys +  0.07 cusr  0.01 csys =  0.12 CPU)
Result: PASS
prove t/ --state=slow,save -j3  0.19s user 0.06s system 6% cpu 4.175 total
[hitode909@superfamilycomputer.local:~/co/slow-test]
% time prove t/  --state=slow,save -j4
t/1.t .. ok
t/2.t .. ok
t/3.t .. ok
t/4.t .. ok
All tests successful.
Files=4, Tests=8,  4 wallclock secs ( 0.03 usr  0.01 sys +  0.09 cusr  0.02 csys =  0.15 CPU)
Result: PASS
prove t/ --state=slow,save -j4  0.19s user 0.06s system 6% cpu 4.159 total
[hitode909@superfamilycomputer.local:~/co/slow-test]
```
