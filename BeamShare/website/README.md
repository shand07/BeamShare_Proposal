# BeamShare — Simple, Secure File Transfer


### What is the software product?
BeamShare is a lightweight file transfer application. One computer runs a small server that shares a chosen folder; other computers connect as clients to upload or download files over reliable TCP. It’s designed to be easy to set up for ad-hoc sharing on a home network, classroom, lab, or small team.

### Possible product names considered
- SwiftDrop
- FileFerry
- LanBridge
- PortaShare
- BeamShare 

### Final name
**BeamShare**

### Potential customers / end users / buyers
- Students and instructors exchanging class files or lab submissions
- Small teams that need a quick way to share builds, assets, or reports
- Home users moving large videos/photos between devices without cloud
- IT help desks transferring diagnostics or drivers during support
- Hackathon participants sharing code/artifacts on a local network

### Potential features & details appealing to users
- **One-click host**: share any folder immediately
- **Progress bars** with ETA and transfer speed
- **Drag-and-drop** uploads (web UI)
- **Simple authentication**: per-session access token or username/password
- **Integrity checks**: SHA-256 hash verification after transfer
- **Resume support** for interrupted transfers (range/chunked transfers)
- **Access controls**: read-only share or allow uploads with quotas
- **Link & QR code** to join quickly on the same LAN
- **Multi-platform**: runs on Windows, macOS, Linux (Python runtime)
- **CLI + minimal GUI** for different user preferences
- **Logging**: who downloaded what & when (CSV/JSON logs)
- **Optional TLS** when certificates are provided (for non-LAN use)

### Product Vision Statement
> For students, home users, and small teams who need a fast, private way to move files without friction, **BeamShare** is a lightweight LAN-first file transfer tool that turns any folder into a share in seconds. Unlike email, thumb drives, or cloud uploads, BeamShare delivers **reliable, resumable TCP transfers with simple authentication and integrity checks**, so teams can share confidently with minimal setup.

---

**Developer:** Sean Hand
