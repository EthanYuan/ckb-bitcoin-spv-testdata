### Difficulty-Change Headers Test Cases

The headers, which in the current directory, are used for testing the bitcoin difficulty change.

Let's denote the interval of Bitcoin difficulty change to be $I_{\mathnormal{change}}$ [^1],
then the heights of headers in the current directory should be $H = H_{first} \cup H_{last}$, where:

```math
H_{first} = \{\, k \cdot I_{\mathnormal{change}} \mid k \in \mathbb{Z}\,\}
```

```math
H_{last}  = \{\, k \cdot I_{\mathnormal{change}} - 1 \mid k \in \mathbb{N}\,\}
```

[^1]: [How often does the network difficulty change?](https://en.bitcoin.it/wiki/Difficulty#How_often_does_the_network_difficulty_change.3F)
