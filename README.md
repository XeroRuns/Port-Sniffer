# Port Sniffer
A simple program that runs through an ip address and looks for open ports and reports them back

# Run
1. Run ```git clone https://github.com/XeroRuns/Port-Sniffer```
2. Run ```cargo run -- <ip>```

# How to use
You can run it with no specification of thread amount

```cargo run -- <ip>```

You can run it with specification of thread amount

```cargo run -- -j <thread amount> <ip>```

# Why
I wrote this to learn a bit more about networking in rust

# License
[MIT](https://opensource.org/license/mit/)