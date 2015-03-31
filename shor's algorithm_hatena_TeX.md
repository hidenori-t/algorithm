#shor's algorithm
[tex: N] を因数分解するにあたり, [tex: a]  は[tex: N]に対して素な数とし,
[tex: a] の[tex: mod \ N] に関する位数,

[tex:
min \\{ x | a\^x = 1 \begin{eqnarray}\pmod{N}\end{eqnarray}\\}
]
つまり, [tex: a\^x ] の周期 [tex: r ] を求める.
* * *

[tex:N = 15  ]
[tex:a = 7 ]
とする.


[tex: 7\^1 = 7 \begin{eqnarray}\pmod{15}\end{eqnarray}]
[tex: 7\^2 = 4 \begin{eqnarray}\pmod{15}\end{eqnarray}]
[tex: 7\^3 = 13 \begin{eqnarray}\pmod{15}\end{eqnarray}]
<span style="color: #ff0000">[tex: 7\^4 = 1 \begin{eqnarray}\pmod{15}\end{eqnarray}]  </span>
[tex: 7\^5 = 7 \begin{eqnarray}\pmod{15}\end{eqnarray}]
[tex: 7\^6 = 4 \begin{eqnarray}\pmod{15}\end{eqnarray}]
[tex: 7\^7 = 13 \begin{eqnarray}\pmod{15}\end{eqnarray}]
<span style="color: #ff0000">[tex: 7\^8 = 1 \begin{eqnarray}\pmod{15}\end{eqnarray}] </span>
[tex: 7\^9 = 7 \begin{eqnarray}\pmod{15}\end{eqnarray}]
...
よって,


周期 [tex:r =min \\{ x | 7\^x = 1 \begin{eqnarray}\pmod{15}\end{eqnarray}\\} = 4]

離散フーリエ変換??
