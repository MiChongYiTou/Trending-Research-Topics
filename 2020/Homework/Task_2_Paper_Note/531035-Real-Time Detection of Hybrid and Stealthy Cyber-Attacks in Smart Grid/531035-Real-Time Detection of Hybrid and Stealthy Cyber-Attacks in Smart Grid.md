论文信息：
标题：Real-Time Detection of Hybrid and Stealthy Cyber-Attacks in Smart Grid
作者：Mehmet Necip Kurt , Yasin Yılmaz , Member, IEEE, and Xiaodong Wang , Fellow, IEEE
链接：https://doi.org/10.1109/TIFS.2018.2854745
出处：IEEE TRANSACTIONS ON INFORMATION FORENSICS AND SECURITY, VOL. 14, NO. 2, FEBRUARY 2019
笔记作者：孙钰皓 2018141531035
论文简要： 
    对于智能电网的安全可靠运行，及时发现网络攻击至关重要。作者提出了一种有效的在线检测算法，用于虚假数据注入和干扰攻击，同时提供未知和时变攻击参数的在线估计和恢复状态估计。
主要内容：
    首先对智能电网中网络攻击与对策进行了简要的说明，攻击者的主要目的是破坏/误导状态估计机制，从而导致智能电网能源管理系统的决策错误。并且说明了此篇文献对现有状况所做出的三点主要贡献。最后介绍了论文的主要框架。
    接着介绍了该系统模型、攻击模型、状态估计机制和问题的求解方法，并且列举出了核心的算法。
    然后提出了一种在线网络攻击检测与估计的算法。并且列举了核心的算法以及公式。
    接着介绍并分析了针对基于cusum的探测器的秘密攻击。同时，针对所考虑的隐形攻击提出了相应的对策。
    然后通过仿真对前文提出的检测方案进行了评估，用前后的对比图有效地进行比较说明。
    最终得出结论，本文研究智能电网中混合FDI干扰攻击的实时检测，并且提出了两种有效地对抗攻击的对策。
创新点：作者将智能电网建模成了一个线性的动态系统，并且提出了一种对未知时变攻击参数有效地在线攻击检测与估计的算法。并且同时考虑到攻击者可以通过隐形攻击来避免检测或者增加检测的时间，作者还提出了额外应对此种情况的策略。
不足：在提出在线网络攻击检测与估计算法时，可能还会有参数调整，并且可能会增加检测的时间和延迟。而且虽然这种机制能够减少在检测攻击时的假警报，但是依旧存在假警报的状况。而且虽然有难度，但是攻击者仍然可以避免自身被检测。