# Supplementary Reading for The OSI Networking Model

In addition to the five layer model we are working with, it’s important to note that other models exist. The traditional TCP/IP Model only has four layers, as it doesn’t differentiate between the physical layer and the data link layer, but is otherwise very similar to the one we’ll be working with. The most well known other model is the OSI model. It’s the model taught by many other networking certificate programs, like Net+ and Cisco’s many networking certifications. The primary difference between our five layer model and the seven layer OSI model is that the OSI model abstracts the application layer into three layers total.
 You can learn more about the OSI Networking Model by checking out these links:

[https://www.sans.org/reading-room/whitepapers/standards/osi-model-overview-543](https://www.sans.org/reading-room/whitepapers/standards/osi-model-overview-543)

[https://en.wikipedia.org/wiki/OSI_model](https://en.wikipedia.org/wiki/OSI_model)

---

# The TCP/IP Five-Layer Network Model

<!DOCTYPE html>
<html>
<head>
</head>
<body>

<table border="1" cellpadding="8" cellspacing="0" style="border-collapse: collapse; width: 100%;">
  <tr>
    <th>Layer</th>
    <th>Protocol data unit (PDU)</th>
    <th>Function</th>
  </tr>
  <tr>
    <td rowspan="3">Host layers</td>
    <td>7</td>
    <td>Application</td>
    <td>Data</td>
    <td>High-level protocols such as for resource sharing or remote file access, e.g. HTTP.</td>
  </tr>
  <tr>
    <td>6</td>
    <td>Presentation</td>
    <td>Translation of data between a networking service and an application; including character encoding, data compression and encryption/decryption</td>
  </tr>
  <tr>
    <td>5</td>
    <td>Session</td>
    <td>Managing communication sessions, i.e., continuous exchange of information in the form of multiple back-and-forth transmissions between two nodes</td>
  </tr>
  <tr>
    <td rowspan="3">Media layers</td>
    <td>4</td>
    <td>Transport</td>
    <td>Segment, Datagram</td>
    <td>Reliable transmission of data segments between points on a network, including segmentation, acknowledgement and multiplexing</td>
  </tr>
  <tr>
    <td>3</td>
    <td>Network</td>
    <td>Packet</td>
    <td>Structuring and managing a multi-node network, including addressing, routing and traffic control</td>
  </tr>
  <tr>
    <td>2</td>
    <td>Data link</td>
    <td>Frame</td>
    <td>Transmission of data frames between two nodes connected by a physical layer</td>
  </tr>
  <tr>
    <td>1</td>
    <td>Physical</td>
    <td>Bit, Symbol</td>
    <td>Transmission and reception of raw bit streams over a physical medium</td>
  </tr>
</table>

</body>
</html>
