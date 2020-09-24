A: strlen(s) < strlen(t) 时strlen(s) - strlen(t) > 0结果依然为1
B: strlen为无符号整型 计算结果依然为无符号整型
C: strlen(s) - strlen(t) > 0 => strlen(s) > strlen(t)