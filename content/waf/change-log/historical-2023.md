---
pcx_content_type: changelog
title: Historical (2023)
weight: 10045
meta:
  description: Changes to WAF managed rulesets done in 2023.
layout: wide
---

# Historical - 2023

{{<table-wrap>}}
<table style="width: 100%">
  <thead>
    <tr>
      <th>Ruleset</th>
      <th>Rule ID</th>
      <th>Legacy Rule ID</th>
      <th>Description</th>
      <th>Change Date</th>
      <th>Old Action</th>
      <th>New Action</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Cloudflare Specials</td>
      <td>...1bc977d1</td>
      <td>N/A</td>
      <td>DotNetNuke - File Inclusion - CVE:CVE-2018-9126, CVE:CVE-2011-1892, CVE:CVE-2022-31474</td>
      <td>2023-12-18</td>
      <td>N/A</td>
      <td>Block</td>
    </tr>
    <tr>
      <td>Cloudflare Specials</td>
      <td>...bb6d4e13</td>
      <td>100615</td>
      <td>Apache Struts - Remote Code Execution - CVE:CVE-2023-50164</td>
      <td>Emergency, 2023-12-14</td>
      <td>N/A</td>
      <td>Block</td>
    </tr>
    <tr>
      <td>Cloudflare Specials</td>
      <td>...8ed2b1d9</td>
      <td>100611</td>
      <td>WordPress:Plugin:WooCommerce - Unauthorized Administrator Access - CVE:CVE-2023-28121</td>
      <td>2023-11-21</td>
      <td>N/A</td>
      <td>Block</td>
    </tr>
    <tr>
      <td>Cloudflare Specials</td>
      <td>...c3b6a372</td>
      <td>100593</td>
      <td>Adobe ColdFusion - Auth Bypass, Remote Code Execution - CVE:CVE-2023-29298, CVE:CVE-2023-38203, CVE:CVE-2023-26360</td>
      <td>2023-11-21</td>
      <td>N/A</td>
      <td>Block</td>
    </tr>
    <tr>
      <td>Cloudflare Specials</td>
      <td>...c54e7046</td>
      <td>100614</td>
      <td>Atlassian Confluence - Code Injection - CVE:CVE-2023-22518</td>
      <td>Emergency, 2023-11-06</td>
      <td>N/A</td>
      <td>Block</td>
    </tr>
    <tr>
      <td>Cloudflare Specials</td>
      <td>...d59a59db</td>
      <td>100609</td>
      <td>Keycloak - SSRF - CVE:CVE-2020-10770</td>
      <td>2023-10-30</td>
      <td>N/A</td>
      <td>Block</td>
    </tr>
    <tr>
      <td>Cloudflare Specials</td>
      <td>...3e3f706d</td>
      <td>100606</td>
      <td>JetBrains TeamCity - Auth Bypass, Remote Code Execution - CVE:CVE-2023-42793</td>
      <td>2023-10-23</td>
      <td>N/A</td>
      <td>Block</td>
    </tr>
    <tr>
      <td>Cloudflare Specials</td>
      <td>...469c4a38</td>
      <td>100607</td>
      <td>Progress WS_FTP - Information Disclosure - CVE:CVE-2023-40044</td>
      <td>2023-10-23</td>
      <td>N/A</td>
      <td>Block</td>
    </tr>
    <tr>
      <td>Cloudflare Specials</td>
      <td>...7ccccdce</td>
      <td>100608</td>
      <td>Progress WS_FTP - Remote Code Execution - CVE:CVE-2023-40044</td>
      <td>2023-10-23</td>
      <td>N/A</td>
      <td>Block</td>
    </tr>
    <tr>
      <td>Cloudflare Specials</td>
      <td>...ec9f34e1</td>
      <td>100604</td>
      <td>
        Atlassian Confluence - Privilege Escalation - CVE:CVE-2023-22515.<br>
        Also released for Cloudflare Free customers, with rule ID ...91935fcb (updated detection logic).
      </td>
      <td>Emergency, 2023-10-11</td>
      <td>N/A</td>
      <td>Block</td>
    </tr>
    <tr>
      <td>Cloudflare Specials</td>
      <td>...ec9f34e1</td>
      <td>100604,100605</td>
      <td>
        Atlassian Confluence - Privilege Escalation - CVE:CVE-2023-22515.<br>
        Also released for Cloudflare Free customers, with rule ID ...91935fcb.
      </td>
      <td>Emergency, 2023-10-04</td>
      <td>N/A</td>
      <td>Block</td>
    </tr>
    <tr>
      <td>Cloudflare Specials</td>
      <td>...34780914</td>
      <td>100532</td>
      <td>Vulnerability scanner activity</td>
      <td>2023-10-02</td>
      <td>N/A</td>
      <td>Block</td>
    </tr>
    <tr>
      <td>Cloudflare Specials</td>
      <td>...066c0c9a</td>
      <td>100602</td>
      <td>Code Injection - CVE:CVE-2023-36845</td>
      <td>Emergency, 2023-09-22</td>
      <td>N/A</td>
      <td>Block</td>
    </tr>
    <tr>
      <td>Cloudflare Specials</td>
      <td>...0746d000</td>
      <td>100603</td>
      <td>Information Disclosure - CVE:CVE-2023-28432</td>
      <td>Emergency, 2023-09-22</td>
      <td>N/A</td>
      <td>Block</td>
    </tr>
    <tr>
      <td>Cloudflare Specials</td>
      <td>...25ba9d7c</td>
      <td>N/A</td>
      <td>SSRF Cloud</td>
      <td>2023-09-18</td>
      <td>N/A</td>
      <td>Disabled</td>
    </tr>
    <tr>
      <td>Cloudflare Specials</td>
      <td>...c5f041ac</td>
      <td>100597</td>
      <td>Information Disclosure - Path Normalization</td>
      <td>2023-09-04</td>
      <td>Log</td>
      <td>Block</td>
    </tr>
    <tr>
      <td>Cloudflare Specials</td>
      <td>...50cec478</td>
      <td>100598</td>
      <td>Remote Code Execution - Common Bash Bypass</td>
      <td>2023-09-04</td>
      <td>Log</td>
      <td>Block</td>
    </tr>
    <tr>
      <td>Cloudflare Specials</td>
      <td>...ec5b0d04</td>
      <td>100599</td>
      <td>Ivanti - Auth Bypass - CVE:CVE-2023-38035</td>
      <td>2023-09-04</td>
      <td>Log</td>
      <td>Block</td>
    </tr>
    <tr>
      <td>Cloudflare Specials</td>
      <td>...6912c055</td>
      <td>100601</td>
      <td>Malware - Polymorphic Encoder</td>
      <td>2023-09-04</td>
      <td>Log</td>
      <td>Block</td>
    </tr>
    <tr>
      <td>Cloudflare Specials</td>
      <td>...8242627b</td>
      <td>100146B</td>
      <td>SSRF Local BETA</td>
      <td>2023-09-04</td>
      <td>Log</td>
      <td>Disabled</td>
    </tr>
    <tr>
      <td>Cloudflare Specials</td>
      <td>...84dadf5a</td>
      <td>100595</td>
      <td>MobileIron - Auth Bypass - CVE:CVE-2023-35082</td>
      <td>2023-08-21</td>
      <td>Log</td>
      <td>Block</td>
    </tr>
    <tr>
      <td>Cloudflare Specials</td>
      <td>...48a60154</td>
      <td>N/A</td>
      <td>SQLi - Keyword + SubExpress + Comment + BETA</td>
      <td>2023-08-21</td>
      <td>N/A</td>
      <td>Disabled</td>
    </tr>
    <tr>
      <td>Cloudflare Specials</td>
      <td>...cac42ce2</td>
      <td>100596</td>
      <td>Citrix Content Collaboration ShareFile - Remote Code Execution - CVE:CVE-2023-24489</td>
      <td>Emergency, 2023-08-17</td>
      <td>N/A</td>
      <td>Block</td>
    </tr>
    <tr>
      <td>Cloudflare Specials</td>
      <td>...c3b6a372</td>
      <td>100593</td>
      <td>Adobe ColdFusion - Auth Bypass, Remote Code Execution - CVE:CVE-2023-29298, CVE:CVE-2023-38203, CVE:CVE-2023-26360</td>
      <td>2023-08-07</td>
      <td>N/A</td>
      <td>Block</td>
    </tr>
    <tr>
      <td>Cloudflare Specials</td>
      <td>...63d65c25</td>
      <td>100594</td>
      <td>Citrix Netscaler ADC - Remote Code Execution - CVE:CVE-2023-3519</td>
      <td>2023-08-07</td>
      <td>Log</td>
      <td>Block</td>
    </tr>
    <tr>
      <td>Cloudflare Specials</td>
      <td>...63d65c25</td>
      <td>100594</td>
      <td>Citrix Netscaler ADC - Remote Code Execution - CVE:CVE-2023-3519</td>
      <td>Emergency, 2023-08-01</td>
      <td>N/A</td>
      <td>Log</td>
    </tr>
    <tr>
      <td>Cloudflare Specials</td>
      <td>...777f5c34</td>
      <td>100590</td>
      <td>Fortigate VPN - Remote Code Execution - CVE:CVE-2023-27997</td>
      <td>2023-07-31</td>
      <td>N/A</td>
      <td>Block</td>
    </tr>
    <tr>
      <td>Cloudflare Specials</td>
      <td>...0bd669ca</td>
      <td>100592</td>
      <td>Code Injection - Generic</td>
      <td>2023-07-31</td>
      <td>N/A</td>
      <td>Block</td>
    </tr>
    <tr>
      <td>OWASP Rules</td>
      <td>...af347fde</td>
      <td>N/A</td>
      <td>944100: Remote Command Execution: Suspicious Java class detected</td>
      <td>2023-07-10</td>
      <td>N/A</td>
      <td>Block</td>
    </tr>
    <tr>
      <td>OWASP Rules</td>
      <td>...9fae472b</td>
      <td>N/A</td>
      <td>944110: Remote Command Execution: Java process spawn (CVE-2017-9805)</td>
      <td>2023-07-10</td>
      <td>N/A</td>
      <td>Block</td>
    </tr>
    <tr>
      <td>OWASP Rules</td>
      <td>...5ab75703</td>
      <td>N/A</td>
      <td>944120: Remote Command Execution: Java serialization (CVE-2015-4852)</td>
      <td>2023-07-10</td>
      <td>N/A</td>
      <td>Block</td>
    </tr>
    <tr>
      <td>OWASP Rules</td>
      <td>...73cd4e53</td>
      <td>N/A</td>
      <td>944210: Magic bytes Detected Base64 Encoded, probable Java serialization in use</td>
      <td>2023-07-10</td>
      <td>N/A</td>
      <td>Block</td>
    </tr>
    <tr>
      <td>OWASP Rules</td>
      <td>...e068f5d3</td>
      <td>N/A</td>
      <td>944300: Base64 encoded string matched suspicious keyword</td>
      <td>2023-07-10</td>
      <td>N/A</td>
      <td>Block</td>
    </tr>
    <tr>
      <td>Cloudflare Specials</td>
      <td>...6f9bfc13</td>
      <td>100590</td>
      <td>VMware - Remote Code Execution - CVE:CVE-2023-20887</td>
      <td>2023-07-05</td>
      <td>N/A</td>
      <td>Block</td>
    </tr>
    <tr>
      <td>Cloudflare Specials</td>
      <td>...fb982fd6</td>
      <td>100008G</td>
      <td>SQLi - Libinject with Body Inspection</td>
      <td>2023-07-05</td>
      <td>N/A</td>
      <td>Disabled</td>
    </tr>
    <tr>
      <td>Cloudflare Specials</td>
      <td>...7bc0259f</td>
      <td>100008NS</td>
      <td>Command Injection - Netcat - Body</td>
      <td>2023-07-05</td>
      <td>N/A</td>
      <td>Disabled</td>
    </tr>
    <tr>
      <td>Cloudflare Specials</td>
      <td>...8559ddfa</td>
      <td>100589</td>
      <td>File Inclusion - WEB-INF</td>
      <td>2023-06-19</td>
      <td>N/A</td>
      <td>Block</td>
    </tr>
    <tr>
      <td>Cloudflare Specials</td>
      <td>...269024be</td>
      <td>100587</td>
      <td>Code Injection - CVE:CVE-2019-18889</td>
      <td>2023-06-19</td>
      <td>N/A</td>
      <td>Block</td>
    </tr>
    <tr>
      <td>Cloudflare Specials</td>
      <td>...6f9bfc13</td>
      <td>100590</td>
      <td>VMware - Remote Code Execution - CVE:CVE-2023-20887</td>
      <td>Emergency, 2023-06-14</td>
      <td>N/A</td>
      <td>Block</td>
    </tr>
    <tr>
      <td>Cloudflare Specials</td>
      <td>...269024be</td>
      <td>100587</td>
      <td>Code Injection - CVE:CVE-2022-23529</td>
      <td>2023-06-12</td>
      <td>N/A</td>
      <td>Block</td>
    </tr>
    <tr>
      <td>Cloudflare Specials</td>
      <td>...3ff033f6</td>
      <td>100588</td>
      <td>MoveIT - SSRF</td>
      <td>Emergency, 2023-06-09</td>
      <td>N/A</td>
      <td>Block</td>
    </tr>
    <tr>
      <td>Cloudflare Specials</td>
      <td>...dae05f0a</td>
      <td>100583</td>
      <td>Sophos - Code Injection - CVE:CVE-2023-1671</td>
      <td>2023-05-22</td>
      <td>N/A</td>
      <td>Block</td>
    </tr>
    <tr>
      <td>Cloudflare Specials</td>
      <td>...dd1b7502</td>
      <td>100584</td>
      <td>Oracle Opera - Code Injection - CVE:CVE-2023-21932</td>
      <td>2023-05-22</td>
      <td>N/A</td>
      <td>Disabled</td>
    </tr>
    <tr>
      <td>Cloudflare Specials</td>
      <td>...18585d20</td>
      <td>100582</td>
      <td>vBulletin - Code Injection - CVE:CVE-2023-25135</td>
      <td>2023-05-02</td>
      <td>N/A</td>
      <td>Block</td>
    </tr>
    <tr>
      <td>Cloudflare Specials</td>
      <td>...49e6b538</td>
      <td>100534</td>
      <td>Webshell Activity</td>
      <td>2023-05-02</td>
      <td>N/A</td>
      <td>Block</td>
    </tr>
    <tr>
      <td>Cloudflare Specials</td>
      <td>...8b036974</td>
      <td>100558</td>
      <td>Malware, Web Shell</td>
      <td>2023-05-02</td>
      <td>N/A</td>
      <td>Log</td>
    </tr>
    <tr>
      <td>Cloudflare Specials</td>
      <td>...dfc9b843</td>
      <td>100580</td>
      <td>XSS - Error handling</td>
      <td>2023-04-11</td>
      <td>N/A</td>
      <td>Block</td>
    </tr>
    <tr>
      <td>Cloudflare Specials</td>
      <td>...2f26b3a7</td>
      <td>100581</td>
      <td>Joomla - Information Disclosure - CVE:CVE-2023-23752</td>
      <td>2023-04-11</td>
      <td>N/A</td>
      <td>Block</td>
    </tr>
    <tr>
      <td>Cloudflare Specials</td>
      <td>...602dabe0</td>
      <td>N/A</td>
      <td>XSS - JavaScript Events</td>
      <td>2023-04-11</td>
      <td>N/A</td>
      <td>Block</td>
    </tr>
    <tr>
      <td>Cloudflare Specials</td>
      <td>N/A</td>
      <td>100546</td>
      <td>XSS - HTML Encoding</td>
      <td>2023-04-11</td>
      <td>N/A</td>
      <td>Block</td>
    </tr>
    <tr>
      <td>Cloudflare Specials</td>
      <td>...a47c4be6</td>
      <td>100577</td>
      <td>Apache Spark - Remote Code Execution - CVE:CVE-2022-33891</td>
      <td>2023-03-20</td>
      <td>N/A</td>
      <td>Block</td>
    </tr>
    <tr>
      <td>Cloudflare Specials</td>
      <td>...54d00d2f</td>
      <td>100578</td>
      <td>GLPI - Remote Code Execution - CVE:CVE-2022-35914</td>
      <td>2023-03-20</td>
      <td>N/A</td>
      <td>Block</td>
    </tr>
    <tr>
      <td>Cloudflare Specials</td>
      <td>...fb4c6991</td>
      <td>100579</td>
      <td>GitLab - Remote Code Execution - CVE:CVE-2021-22205</td>
      <td>2023-03-20</td>
      <td>N/A</td>
      <td>Block</td>
    </tr>
    <tr>
      <td>Cloudflare Specials</td>
      <td>...ad679b95</td>
      <td>100575</td>
      <td>ZK Framework - Information Disclosure - CVE:CVE-2022-36537</td>
      <td>2023-03-13</td>
      <td>N/A</td>
      <td>Block</td>
    </tr>
    <tr>
      <td>Cloudflare Specials</td>
      <td>...f2cc4e84</td>
      <td>100524</td>
      <td>Java - Remote Code Execution</td>
      <td>2023-03-06</td>
      <td>N/A</td>
      <td>Block</td>
    </tr>
    <tr>
      <td>Cloudflare Specials</td>
      <td>...30d612c4</td>
      <td>100572</td>
      <td>Java - Remote Code Execution - URL</td>
      <td>2023-03-06</td>
      <td>N/A</td>
      <td>Block</td>
    </tr>
    <tr>
      <td>Cloudflare Specials</td>
      <td>...9497744a</td>
      <td>100570</td>
      <td>FortiNAC - Remote Code Execution - CVE:CVE-2022-39952</td>
      <td>2023-03-06</td>
      <td>N/A</td>
      <td>Block</td>
    </tr>
    <tr>
      <td>Cloudflare Specials</td>
      <td>...5d38ed42</td>
      <td>100564</td>
      <td>Oracle E-Business Suite - Remote Code Execution - CVE:CVE-2022-21587</td>
      <td>2023-02-27</td>
      <td>N/A</td>
      <td>Block</td>
    </tr>
    <tr>
      <td>Cloudflare Specials</td>
      <td>...d7e78753</td>
      <td>100566</td>
      <td>Ruby on Rails - Remote Code Execution</td>
      <td>2023-02-27</td>
      <td>N/A</td>
      <td>Block</td>
    </tr>
    <tr>
      <td>Cloudflare Specials</td>
      <td>...72612a5b</td>
      <td>100568</td>
      <td>Cacti - Remote Code Execution - CVE:CVE-2022-46169</td>
      <td>2023-02-27</td>
      <td>N/A</td>
      <td>Block</td>
    </tr>
    <tr>
      <td>Cloudflare Specials</td>
      <td>...a6fda143</td>
      <td>100563</td>
      <td>Template Injection</td>
      <td>2023-02-13</td>
      <td>N/A</td>
      <td>Block</td>
    </tr>
    <tr>
      <td>Cloudflare Specials</td>
      <td>...b090ba9a</td>
      <td>100303</td>
      <td>Command Injection - Nslookup</td>
      <td>2023-02-13</td>
      <td>N/A</td>
      <td>Block</td>
    </tr>
    <tr>
      <td>Cloudflare Specials</td>
      <td>...0550c529</td>
      <td>100016</td>
      <td>Version Control - Information Disclosure</td>
      <td>2023-02-13</td>
      <td>N/A</td>
      <td>Block</td>
    </tr>
    <tr>
      <td>Cloudflare Specials</td>
      <td>...d3cdd6ac</td>
      <td>100561</td>
      <td>Remote Code Execution - Double Extension</td>
      <td>2023-02-13</td>
      <td>N/A</td>
      <td>Block</td>
    </tr>
    <tr>
      <td>Cloudflare Specials</td>
      <td>...f2cc4e84</td>
      <td>100524</td>
      <td>Java - Remote Code Execution</td>
      <td>2023-02-06</td>
      <td>N/A</td>
      <td>Block</td>
    </tr>
    <tr>
      <td>Cloudflare Specials</td>
      <td>...1b4e622e</td>
      <td>100560</td>
      <td>Microsoft Exchange - Broken Authentication - CVE:CVE-2021-33766</td>
      <td>2023-02-06</td>
      <td>N/A</td>
      <td>Block</td>
    </tr>
    <tr>
      <td>Cloudflare Specials</td>
      <td>...de5e2367</td>
      <td>N/A</td>
      <td>XSS - JavaScript Events</td>
      <td>2023-01-30</td>
      <td>N/A</td>
      <td>Block</td>
    </tr>
    <tr>
      <td>Cloudflare Specials</td>
      <td>...4c2e80c3</td>
      <td>100557</td>
      <td>Code Injection - JavaScript</td>
      <td>2023-01-30</td>
      <td>N/A</td>
      <td>Block</td>
    </tr>
    <tr>
      <td>Cloudflare Specials</td>
      <td>...65414846</td>
      <td>100559</td>
      <td>Prototype pollution Attack, Headers</td>
      <td>2023-01-30</td>
      <td>N/A</td>
      <td>Block</td>
    </tr>
    <tr>
      <td>Cloudflare OWASP</td>
      <td>...fc25d2f1f</td>
      <td>N/A</td>
      <td>Rollback Cloudflare OWASP to version 3.3.3 from 3.3.4</td>
      <td>2023-01-24</td>
      <td>N/A</td>
      <td>N/A</td>
    </tr>
    <tr>
      <td>Cloudflare Specials</td>
      <td>...8b036974</td>
      <td>100558</td>
      <td>Malware, Web Shell</td>
      <td>2023-01-16</td>
      <td>N/A</td>
      <td>Log</td>
    </tr>
    <tr>
      <td>Cloudflare Specials</td>
      <td>N/A</td>
      <td>100135C</td>
      <td>XSS - JavaScript Events</td>
      <td>2023-01-16</td>
      <td>N/A</td>
      <td>Block</td>
    </tr>
    <tr>
      <td>Cloudflare OWASP</td>
      <td>...fc25d2f1f</td>
      <td>N/A</td>
      <td>Upgrading Cloudflare OWASP to version 3.3.4</td>
      <td>2023-01-16</td>
      <td>N/A</td>
      <td>N/A</td>
    </tr>
    <tr>
      <td>Cloudflare Specials</td>
      <td>...b604fb62</td>
      <td>100551B</td>
      <td>Microsoft Exchange SSRF and RCE vulnerability 2 - CVE:CVE-2022-41040, CVE:CVE-2022-41082</td>
      <td>2023-01-09</td>
      <td>N/A</td>
      <td>Block</td>
    </tr>
  </tbody>
</table>
{{</table-wrap>}}