## Welcome to Silicon Silk

Silicon neobank

### “Electronic Money Institution" Licensed

Silicon Bank's new generation of digital banking products
Silicon Business Enterprise Wallet (B2B, B2C) + OEM / Agent

```Silicon neobank
OTA / Marketplace technology financial service platform

Provide customized E-wallet + card for OTA platform / Marketplace
Provide E-payment + membership management + mobile marketing solutions for enterprises
Supplement the lack of digital banking and financing value-added services for PSP companies


Better Finance ,Better life.

### More effective
### More convenient
### More Compliant 
### More flexible

Silicon Pay
https://www.siliconsilk.com





### Contact
Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.


<!DOCTYPE html>
<html lang="en">

<head>
<title>Handshake Developer Documentation</title>

<meta name="generator" content="pandoc">
<meta name="viewport" content="width=device-width,initial-scale=1">
<meta http-equiv="X-UA-Compatible" content="IE=edge">
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />

<link rel="icon" type="image/ico" href="/img/favicon.ico" />
<link rel="stylesheet" type="text/css" href="/css/github-markdown.min.css" />
<link rel="stylesheet" type="text/css" href="/css/main.css" />
</head>

<body>
<header>
  <a href="/"><img alt="Handshake logo" src="/img/logo.svg" /></a>
</header>

<main>
<nav><div class="wrapper">
  <ul>
    <li><strong>INSTALL</strong></li>
    <li><a id="install-mac"   href="/guides/mac-install.html">macOS</a></li>
    <li><a id="install-linux"   href="/guides/linux-install.html">Linux</a></li>
    <li><a id="install-win"   href="/guides/win-install.html">Windows</a></li>
  </ul>
  <ul>
    <li><strong>GUIDES</strong></li>
    <li><a id="guides-config"   href="/guides/config.html">HSD Configuration</a></li>
    <li><a id="guides-events"   href="/guides/events.html">Events & Sockets</a></li>
    <li><a id="guides-claims"   href="/guides/claims.html">Name Claims</a></li>
    <li><a id="guides-auctions"   href="/guides/auctions.html">Name Auctions</a></li>
    <li><a id="guides-wallet"   href="/guides/wallet.html">Wallet Setup</a></li>
    <li><a id="guides-protocol"   href="/guides/protocol.html">Protocol Summary</a></li>
  </ul>
  <ul>
    <li><strong>DOCUMENTATION</strong></li>
    <li><a href="/api-docs">API Docs</a></li>
    <li><a href="/docs">Full Documentation</a></li>
  </ul>
  <ul>
    <li><strong>PROTOCOL</strong></li>
    <li><a href="/files/handshake.txt">Paper</a></li>
  </ul>
</div></nav>

<section class="markdown-body">
<pre class="lynx">
    ___   
   /\__\  
  /:/__/_ 
 /::\/\__\
 \/\::/  /
   /:/  / 
   \/__/  
</pre>

<h2 id="introduction">Introduction</h2>
<p>Handshake is a UTXO-based blockchain protocol which manages the registration, renewal and transfer of DNS top-level domains (TLDs). Our naming protocol differs from its predecessors in that it has no concept of namespacing or subdomains at the consensus layer. Its purpose is <em>not</em> to replace DNS, but to replace the root zone file and the root servers.</p>
<p>The full node daemon, <a href="https://github.com/handshake-org/hsd">hsd</a>, is written in Javascript and is a fork of <a href="https://bcoin.io">bcoin</a>. By running a full node, you can participate in securing the network and serving the root zone file embedded in the blockchain.</p>
<p>We also have a light client, <a href="https://github.com/handshake-org/hnsd">hnsd</a>, which is written in C. It can verify blockchain data and serve provable resource records without having the resource requirements of a full node. It also acts as an authoritative name server over the Handshake root zone, and a recursive name server pointed at the authoritative name server.</p>
<p>By installing and/or contributing to Handshake, you are participating in a decentralized open platform owned by the commons.</p>
<h3 id="source-code">Source Code</h3>
<p>The latest source code is available on <a href="https://github.com/handshake-org">GitHub</a> under the <a href="https://opensource.org/licenses/mit-license.php">MIT license</a>.</p>
<h3 id="coins">Coins</h3>
<p>Handshake utilizes a utility coin system for name registration. Handshake depends on the free and open source community to take ownership and decentralize the system <a href="https://handshake.org">https://handshake.org</a>.</p>
<h3 id="mailing-list">Mailing List</h3>
<p>You can subscribe to the GNU Mailman mailing list by e-mailing ‘subscribe’ to <a href="mailto:devs@handshake.org">devs@handshake.org</a>.</p>
<h3 id="irc">IRC</h3>
<p>A community IRC channel exists on Freenode in irc.freenode.net:#handshake.</p>

<hr/>
<h4>See a mistake? Open a pull request.</h4>
<a href="https://github.com/handshake-org/handshake-org.github.io/blob/master/src/index.md">https://github.com/handshake-org/handshake-org.github.io/blob/master/src/index.md</a>
</section>
</main>

<footer id="footer">
  &copy;&nbsp;2018 Handshake Community<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">(Creative Commons Attribution-ShareAlike 4.0 International License)</a>
</footer>
</body>

</html>
