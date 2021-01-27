# Add-ons Blocking Process

Add-ons enable users to add features to Thunderbird for a personalized user experience. Most add-ons are created with the best intent, providing users with useful and delightful features. However, add-ons can also be used to compromise personal data and security.

When the Thunderbird Team becomes aware of add-ons that go against user expectations or otherwise risk user privacy and security, it takes steps to block them from running in Thunderbird. This may happen proactively, or in response to an abuse report.

The following describes our common practices for dealing with such add-ons.

### Security Over Choice

When deciding whether to block an add-on from running in Thunderbird, we ask whether the risk is so great that it outweighs the user’s choice to install the software, the utility it provides, as well as the developer’s freedom to distribute and control their software. If we encounter a situation where we cannot make a clear-cut decision, we will err on the side of security to protect the user.

### Blocking Criteria

The Thunderbird Team will block add-ons with the following characteristics:

* They contain critical security vulnerabilities
* They compromise user privacy
* They severely circumvent user consent or control
* They cause severe stability and performance issues in Thunderbird
* They contain obfuscated or comparably unreadable code (see Mozilla’s [examples](https://extensionworkshop.com/documentation/publish/source-code-submission/#use-of-obfuscated-code) of prohibited use of obfuscated code)

Additionally, add-ons listed on ATN will be blocked if they seem to intentionally violate [ATN policy](review-policy-for-thunderbird-add-ons.md).

Add-ons that appear to be clones, repeats or close copies of already blocked add-ons will also be removed. If an issue is known to affect only a subset of versions, the block may be applied to the affected versions specifically. 

### Developer Outreach

When we decide to block an add-on, we may reach out to the developer if we believe the issue can be remedied. As the security of users may be at stake, we require developers to respond within three days. If no response is received within this timeframe, or the developer isn’t able to address the issue, we may proceed with the block.

More commonly, we will not reach out to developers prior to blocking if it appears that the add-on is intentionally violating our policies, or the violation is sufficiently severe.

### Requesting a Block

If you have encountered an add-on that you believe meets the criteria for being blocked, you may [request a block](http://bugzilla.mozilla.org/form.blocklist) **\[todo: update link\]**. Note that developers cannot request a block of their own add-ons [Remark by Dirk: Why?]

### Blocking Other Types of Third Party Software

In addition to add-ons, the Thunderbird Team may also block other types of software that pose a risk to the user.

The Thunderbird Team may limit hardware acceleration features of graphics cards for certain graphics driver versions in accordance with [Mozilla’s graphics driver blocks](https://wiki.mozilla.org/Blocklisting/Graphics) policy. This is done for stability reasons, to avoid driver crashes that would interrupt the user.

In addition, we may block certain injected third party libraries that interfere with the functionality of Thunderbird.
