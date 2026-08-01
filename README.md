# RelayKey

Use another computer from wherever you are — its screen, its terminal, its
files — even when it sits behind a home router or an office firewall.

Nothing you do passes through a server we can read. There is no account to
sign up for and no password to choose.

## Start here

**1. Open [app.relaykey.net](https://app.relaykey.net) and create an account.**
It takes a few seconds and works in any browser. Nothing to install on the
computer you are sitting at.

**2. Install RelayKey on the computer you want to reach.**

On Windows, download `relaykey-agent-gui-windows-amd64.exe` from
[Releases](../../releases/latest) and run it.

On a Mac or Linux machine, paste this into its terminal:

```sh
curl -fsSL https://github.com/ptrinh/relaykey-public/releases/latest/download/install.sh | sh
```

**3. Pair the two.** In the app, choose **Add machine** — it shows you a code.
The machine asks for that code. Type it in, and the machine appears in your
list.

That is the whole setup. From then on you get its terminal, its desktop, its
files and a browser that runs on it, from the app or from any browser.

## Downloads

Everything is on the [Releases page](../../releases/latest). If you followed
the steps above you do not need this table.

| What you want | File |
|---|---|
| Windows — the computer you want to reach | `relaykey-agent-gui-windows-amd64.exe` |
| Windows — the app you control from | `relaykey-client-gui-windows-amd64.exe` |
| Mac — the app you control from | `relaykey-client-gui-macos-arm64.zip` |
| Mac or Linux — the computer you want to reach | `install.sh` (see above) |
| Servers, or no desktop at all | `relaykey-agent-cli-…` |

On an older Intel or ARM machine, pick the file ending in `-amd64` or `-arm64`
to match it. `SHA256SUMS` lets you check a download arrived intact.

The Mac app updates itself: **Settings → About → Check for Updates**.

## Links

- Website — https://relaykey.net
- Use it in a browser — https://app.relaykey.net
- Questions and sales — sales@relaykey.net

Proprietary software. All rights reserved. Sold by SENPRINTS LLC. No refunds.

© Phil Trinh
