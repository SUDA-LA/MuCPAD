# Data content：

The txt file contains 20 randomly selected predicates from each of the six domains "Source, PB, PC, ZX, LAW, MED", for a total of 120 predicates.

# Data forms：
   - Take "2418	他 回家 以后 , 表示 道歉 , 并且 保证 以后 再 也 不 跑 了 。	8	0_agent&2_time&13_pred-patient"  as an example:
     -  "2418"  is the index of task;
     -  "他 回家 以后 , 表示 道歉 , 并且 保证 以后 再 也 不 跑 了 。"  is the sentence;
     -  '8' is the index of the predicate "保证", the word index start from 0;
     - "0_agent&2_time&13_pred-patient" is the labeled result, where each argument is separated by ''&'';
     - "0_agent" is an argument of the predicate "保证", where "0" is the index of the argument "他" and "agent" is the semantic role label of the argument "他".
