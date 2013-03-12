ec2mux
------
Light wrapper around [swarm](http://github.com/mapbox/swarm) to allow connecting to multiple EC2s in tmux.

    sudo npm install -g ec2mux

    Usage:
      ec2mux [-i keyfile] [user@]<swarm>
    Example:
      ec2mux demo                        connect to ec2s tagged Swarm:demo
      ec2mux custom@demo                 connect as user custom
      ec2mux -i ~/.ssh/mykey.pem demo    use mykey.pem
