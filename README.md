# cacti-yamaha-template

Cacti's Graph template files and Data template files for YAMAHA RTX1200 router.

* YAMAHA RTX1200 (Japanese): http://jp.yamaha.com/products/network/routers/rtx1200/
* Cacti: http://www.cacti.net

## Contents

Graph/Data template for:

* CPU usage graph (100 percentile)
    - OID: .1.3.6.1.4.1.1182.2.1.4.0
* Memory usage graph (100 percentile)
    - OID: .1.3.6.1.4.1.1182.2.1.5.0 (average in 5 sec)
    - OID: .1.3.6.1.4.1.1182.2.1.6.0 (average in 1 min)
    - OID: .1.3.6.1.4.1.1182.2.1.7.0 (average in 5 min)
* Temperature graph (by Celsius)
    - OID: .1.3.6.1.4.1.1182.2.1.15.0

## How to use

1. Place this template files (xml) to your local box (not a server)
2. Install cacti
3. Login to cacti, open [console]->[Import Templates]
4. Specify template files at "Inport Template from Local File"
5. Press [Import]
6. Now you can create graphs for CPU, Memory, Temperture
