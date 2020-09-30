# 学习资料
  * ## [数学](./docs/1.math/math.md)
  * ## [语文](./docs/2.chinese/chinese.md)
  * ## [英语](./docs/3.english/english.md)
  * ## [物理](./docs/4.physics/physics.md)
  * ## [化学](./docs/5.chemistry/chemistry.md)
  * ## [生物](./docs/6.biology/biology.md)
  * ## [道德](./docs/7.ethics/ethics.md)
  * ## [历史](./docs/8.history/history.md)
  * ## [地理](./docs/9.geography/geography.md)


# Design Outline:
## folders:
### 1. Math
#### 1.1. Books
#### 1.2. Chapters
#### 1.3. Steps
#### 1.4. Pasts
#### 1.5. Mocks


gantt         
       dateFormat  YYYY-MM-DD   
       title 使用mermaid语言定制甘特图

       section 任务1
       已完成的任务           :done,    des1, 2014-01-06,2014-01-08
       正在进行的任务               :active,  des2, 2014-01-09, 3d
       待完成任务1               :         des3, after des2, 5d
       待完成任务2              :         des4, after des3, 5d

       section 关键任务
       已完成的关键任务 :crit, done, 2014-01-06,24h
       已完成的关键任务2         :crit, done, after des1, 2d
       正在进行的关键任务             :crit, active, 3d
       待完成的关键任务        :crit, 5d
       待完成任务           :2d
       待完成任务2                      :1d

       section 文档编写
       描述甘特图语法               :active, a1, after des1, 3d
       完成甘特图实例1      :after a1  , 20h
       完成甘特图实例2    :doc1, after a1  , 48h
