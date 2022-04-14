## Supported Network Protocols


### Network layer protocol support

Currently only `IPv4` is supported and was tested extensively:

| Network protocol   | Status |
|--------------------|--------|
| IPv4               | ✅     |
| IPv6               | ?      |
| IGMP               | ?      |
| NDP                | ?      |
| ECN                | ?      |
| IPSec              | ?      |

### Transport layer protocol support

Currently only `TCP`, `UDP` and `ICMP` protocols were tested extensively:

| Transport protocol | Status |
|--------------------|--------|
| TCP                | ✅     |
| UDP                | ✅     |
| ICMP               | ✅     |
| SCTP               | ?      |
| DCCP               | ?      |
| RSVP               | ?      |
| QUIC               | ?      |

### DNS Record Type Support

| DNS Record Type | Status |
|-----------------|--------|
| A               | ✅      |
| AAAA            | ✅      |
| CNAME           | ✅      |
| NS              | ✅      |
| TXT             | ✅      |
| SOA             | ✅      |
| PTR             | ✅      |
| NULL            | ✅      |
| MX              | ✅      |
| ANY             | ✅      |

<br />

Legend: ✅ - currently supported 🏃 - in progress 🙅 - not applicable `?` - unknown / not tested

<br />

- Something is missing? Please create a [✨ feature request](https://github.com/github/gh-net/issues/new?assignees=&labels=enhancement&template=feature_request.md&title=).
- Something is incorrect? Please create a [🐛 bug report](https://github.com/github/gh-net/issues/new?assignees=&labels=bug&template=bug_report.md&title=).
- For list of known issues refer to [👉 this doc](./docs/KNOWN_ISSUES.md).
