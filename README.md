# build

go get github.com/miekg/dns


go build -o resolve


# usage

list google sites in top 500

./resolve -i top500.txt | grep "google.com"

| domain                | namserver        | nameserver      | status   |
| --------------------- |:----------------:|:---------------:|:--------:|
| youtube.com           | ns1.google.com.  | ns3.google.com. | SUCCESS  |
| google.com            | ns3.google.com.  | ns2.google.com. | SUCCESS  |
| blogspot.com          | ns1.google.com.  | ns2.google.com. | SUCCESS  |
| youtu.be              | ns2.google.com.  | ns1.google.com. | SUCCESS  |
| goo.gl                | ns3.google.com.  | ns2.google.com. | SUCCESS  |
| google.de             | ns4.google.com.  | ns2.google.com. | SUCCESS  |
| blogger.com           | ns1.google.com.  | ns3.google.com. | SUCCESS  |
| feedburner.com        | ns1.google.com.  | ns3.google.com. | SUCCESS  |
| google.co.uk          | ns1.google.com.  | ns2.google.com. | SUCCESS  |
| blogspot.co.uk        | ns4.google.com.  | ns2.google.com. | SUCCESS  |
| doubleclick.net       | ns2.google.com.  | ns3.google.com. | SUCCESS  |
| google.fr             | ns1.google.com.  | ns3.google.com. | SUCCESS  |
| google.ca             | ns3.google.com.  | ns1.google.com. | SUCCESS  |
| googleusercontent.com | ns1.google.com.  | ns2.google.com. | SUCCESS  |
| blogspot.com.es       | ns2.google.com.  | ns4.google.com. | SUCCESS  |
| blogspot.de           | ns4.google.com.  | ns3.google.com. | SUCCESS  |
| blogspot.ca           | ns4.google.com.  | ns2.google.com. | SUCCESS  |
| google.nl             | ns4.google.com.  | ns3.google.com. | SUCCESS  |
| blogspot.fr           | ns1.google.com.  | ns2.google.com. | SUCCESS  |
| google.com.br         | ns2.google.com.  | ns4.google.com. | SUCCESS  |
| google.com.au         | ns3.google.com.  | ns1.google.com. | SUCCESS  |
| android.com           | ns1.google.com.  | ns4.google.com. | SUCCESS  |
| blogspot.in           | ns1.google.com.  | ns3.google.com. | SUCCESS  |
| blogspot.jp           | ns1.google.com.  | ns3.google.com. | SUCCESS  |

