+++
title = "The informal report from the RFC 1149 event"
date = "2001-04-28"
tags = []
+++

<p>Finally, rfc 1149 is implemented! On saturday 28th of april 2001, the worlds very first rfc 1149 network was tested. The weather was quite nice, despite being in one of the most rainy places in Norway.</p>
<p>The ping was started approximately at 12:15. We decided to do a 7 1/2 minute interval between the ping packets, that would leave a couple of packets unanswered, given ideal situations. Things didn’t happen quite that way, though. It happened that the neighbour had a flock of pigeons flying. Our pigeons didn’t want to go home at once, they wanted to fly with the other pigeons instead. And who can blame them, when the sun was finally shining after a couple of days?</p>
<p>But the instincts won at last, and after about an hour of fun, we could see a couple of pigeons breaking out of the flock and heading in the right direction. There was much cheering. Apparantly, it WAS our pigeons, because not long after, we got a report from the other site that the first pigeon was sitting on the roof.</p>
<p>And finally, the first return pigeon arrived. The packet was carefully removed from the leg, unrolled and scanned. After manually verifying the OCR and correcting the few mistakes (gocr is quite good, but it *did* have problems recognizing F’s in my end), the packet was accepted as a valid packet, and there was much cheering about what we saw:</p>
<pre>64 bytes from 10.0.3.1: icmp_seq=0 ttl=255 time=6165731.1 ms
</pre>
<p>The remaining pigeons arrived simultaneously. Two of them didn’t have any IP packets, though, it turned out that things had been so busy at the other end that they forgot to shut the pigeon cage, and the remaining two pigeons escaped without an IP packet. There was only six return pigeons, thus we got four ping replys, with ping times varying from 3211 to 6389 seconds. I guess this is a new record for ping times…</p>
<p>The implementation was declared a success. Now, we’re waiting for someone to write other implementations, so that we can do interoperability tests, and maybe we finally can get the RFC into the standards track…</p>
