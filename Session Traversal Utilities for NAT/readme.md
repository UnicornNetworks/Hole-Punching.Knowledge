quote:
"That’s two NATs, no open ports. Historically, people would ask you to enable uPnP on your firewall, but that rarely works and even when it does work, it usually works dangerously well until administrators turn it off.

For now, suffice it to say that Tailscale uses several very advanced techniques, based on the Internet STUN and ICE standards, to make these connections work even though you wouldn’t think it should be possible. This avoids the need for firewall configurations or any public-facing open ports, and thus greatly reduces the potential for human error.

For all the gory details, see my teammate Dave Anderson’s post: How NAT traversal works."
- https://tailscale.com/blog/how-tailscale-works
