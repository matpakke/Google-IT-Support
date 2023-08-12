# Supplementary Reading for The OSI Networking Model

In addition to the five layer model we are working with, it’s important to note that other models exist. The traditional TCP/IP Model only has four layers, as it doesn’t differentiate between the physical layer and the data link layer, but is otherwise very similar to the one we’ll be working with. The most well known other model is the OSI model. It’s the model taught by many other networking certificate programs, like Net+ and Cisco’s many networking certifications. The primary difference between our five layer model and the seven layer OSI model is that the OSI model abstracts the application layer into three layers total.
 You can learn more about the OSI Networking Model by checking out these links:

[https://www.sans.org/reading-room/whitepapers/standards/osi-model-overview-543](https://www.sans.org/reading-room/whitepapers/standards/osi-model-overview-543)

[https://en.wikipedia.org/wiki/OSI_model](https://en.wikipedia.org/wiki/OSI_model)

---

# The TCP/IP Five-Layer Network Model

<style>
    element {
  margin: 1em auto 1em auto;
}
  @media screen
.wikitable {
  background-color: #f8f9fa;
  color: #202122;
  margin: 1em 0;
  border: 1px solid #a2a9b1;
  border-collapse: collapse;
}
  @media screen
table {
  font-size: 100%;
}
  @media screen
.vector-body {
  font-size: 0.875em;
  font-size: calc(1em * 0.875);
  line-height: 1.6;
}
  @media screen
.vector-feature-zebra-design-disabled .mw-body, .vector-feature-zebra-design-disabled .parsoid-body {
  direction: ltr;
}
  @media screen
.vector-feature-zebra-design-disabled body {
  color: #202122;
}
  @media screen
html, body {
  font-family: sans-serif;
}
  @media screen
html {
  font-size: 100%;
}
Overlay Grid
Grid Display Settings
margin
border
padding
958.4×341.6
960×343.2
static
  box-sizing
  border-box
  display
  table
  float
  none
  line-height
  22.4px
  position
  static
  z-index
  auto

</style>

<div class="wikitable">

<table class="wikitable" style="margin: 1em auto 1em auto;">
  <caption>OSI model </caption>
  <tbody>
    <tr>
      <th colspan="3">Layer </th>
      <th>
        <a href="/wiki/Protocol_data_unit" title="Protocol data unit">Protocol data unit</a> (PDU)
      </th>
      <th>Function <sup id="cite_ref-27" class="reference">
          <a href="#cite_note-27">[27]</a>
        </sup>
      </th>
    </tr>
    <tr>
      <th rowspan="4">Host <br>layers </th>
      <td style="background:#d8ec9b;">7 </td>
      <td style="background:#d8ec9b;">
        <a href="/wiki/Application_layer" title="Application layer">Application</a>
      </td>
      <td style="background:#d8ec9c;" rowspan="3">
        <a href="/wiki/Data_(computing)" class="mw-redirect" title="Data (computing)">Data</a>
      </td>
      <td style="background:#d8ec9c;">High-level protocols such as for resource sharing or remote file access, e.g. <a href="/wiki/Hypertext_Transfer_Protocol" class="mw-redirect" title="Hypertext Transfer Protocol">HTTP</a>. </td>
    </tr>
    <tr>
      <td style="background:#d8ec9b;">6 </td>
      <td style="background:#d8ec9b;">
        <a href="/wiki/Presentation_layer" title="Presentation layer">Presentation</a>
      </td>
      <td style="background:#d8ec9b;">Translation of data between a networking service and an application; including <a href="/wiki/Character_encoding" title="Character encoding">character encoding</a>, <a href="/wiki/Data_compression" title="Data compression">data compression</a> and <a href="/wiki/Encryption" title="Encryption">encryption/decryption</a>
      </td>
    </tr>
    <tr>
      <td style="background:#d8ec9b;">5 </td>
      <td style="background:#d8ec9b;">
        <a href="/wiki/Session_layer" title="Session layer">Session</a>
      </td>
      <td style="background:#d8ec9b;">Managing communication <a href="/wiki/Session_(computer_science)" title="Session (computer science)">sessions</a>, i.e., continuous exchange of information in the form of multiple back-and-forth transmissions between two nodes </td>
    </tr>
    <tr>
      <td style="background:#e7ed9c;">4 </td>
      <td style="background:#e7ed9c;">
        <a href="/wiki/Transport_layer" title="Transport layer">Transport</a>
      </td>
      <td style="background:#e7ed9c;">
        <a href="/wiki/Packet_segmentation" title="Packet segmentation">Segment</a>, <a href="/wiki/Datagram" title="Datagram">Datagram</a>
      </td>
      <td style="background:#e7ed9c;">Reliable transmission of data segments between points on a network, including <a href="/wiki/Packet_segmentation" title="Packet segmentation">segmentation</a>, <a href="/wiki/Acknowledgement_(data_networks)" title="Acknowledgement (data networks)">acknowledgement</a> and <a href="/wiki/Multiplexing" title="Multiplexing">multiplexing</a>
      </td>
    </tr>
    <tr>
      <th rowspan="3">Media <br>layers </th>
      <td style="background:#eddc9c;">3 </td>
      <td style="background:#eddc9c;">
        <a href="/wiki/Network_layer" title="Network layer">Network</a>
      </td>
      <td style="background:#eddc9c;">
        <a href="/wiki/Network_packet" title="Network packet">Packet</a>
      </td>
      <td style="background:#eddc9c;">Structuring and managing a multi-node network, including <a href="/wiki/Address_space" title="Address space">addressing</a>, <a href="/wiki/Routing" title="Routing">routing</a> and <a href="/wiki/Network_traffic_control" title="Network traffic control">traffic control</a>
      </td>
    </tr>
    <tr>
      <td style="background:#e9c189;">2 </td>
      <td style="background:#e9c189;">
        <a href="/wiki/Data_link_layer" title="Data link layer">Data link</a>
      </td>
      <td style="background:#e9c189;">
        <a href="/wiki/Frame_(networking)" title="Frame (networking)">Frame</a>
      </td>
      <td style="background:#e9c189;">Transmission of data frames between two nodes connected by a physical layer </td>
    </tr>
    <tr>
      <td style="background:#e9988a;">1 </td>
      <td style="background:#e9988a;">
        <a href="/wiki/Physical_layer" title="Physical layer">Physical</a>
      </td>
      <td style="background:#e9988a;">
        <a href="/wiki/Bit" title="Bit">Bit</a>, <a href="/wiki/Symbol_rate#Symbols" title="Symbol rate">Symbol</a>
      </td>
      <td style="background:#e9988a;">Transmission and reception of raw bit streams over a physical medium </td>
    </tr>
  </tbody>
</table>

</div>