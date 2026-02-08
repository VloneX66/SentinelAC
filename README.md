Sentinel is a low-level, packet-driven anti-cheat system built for modern Minecraft servers (1.21.4+).  
It is not designed to be loud. It is designed to be correct.  
Sentinel does not chase cheats. It waits, observes, and confirms.

    SENTINEL ANTI-CHEAT

> Trust the server.
> Distrust the client.
> Prove everything.

DESIGN MENTALITY
=====================

- The client is hostile
- Lag is exploitable
- Single checks are meaningless
- Precision exposes automation
- Humans are inconsistent
- Cheats are not

Every system in Sentinel is built on these assumptions.

CORE SYSTEMS
===============================================================================

[ PACKET LAYER ]
- Raw packet timing
- Packet order validation
- Packet manipulation detection

[ TIME & DESYNC ENGINE ]
- Timer abuse
- Blink
- Artificial lag

[ MOVEMENT ENGINE ]
- Server-side physics reconstruction
- Speed, fly, glide, phase detection

[ COMBAT ENGINE ]
- Rotation mathematics
- Raytrace validation
- Reach & hitbox analysis

[ BEHAVIOR ENGINE ]
- Long-term player profiling
- Historical consistency analysis

[ DECISION ENGINE ]
- Evidence-based punishment
- Multi-engine correlation

No system is trusted alone.

DETECTION SCOPE
===============================================================================

Sentinel detects, among others:

- Speed (multi-layer, physics-based)
- Fly / Glide / Elytra abuse
- Timer & packet acceleration
- Blink & fake lag
- KillAura (pattern & math-based)
- AimAssist (precision modeling)
- Reach (dynamic, context-aware)
- AutoClicker (statistical)
- Velocity manipulation

Detection is deterministic first,
behavioral second.


WHAT SENTINEL DOES NOT DO
===============================================================================

- No instant bans by default
- No static thresholds
- No Bukkit-event-only checks
- No trust in client-side flags
- No public detection logic

If it looks simple, it is not Sentinel.


PUNISHMENT PHILOSOPHY
===============================================================================

observe → correlate → confirm → mitigate → punish

Punishment is staged.

Cheaters should feel:
"Something is wrong."

Before staff ever see a ban screen.


PERFORMANCE
===============================================================================

- Async-first architecture
- Lock-free data structures
- Main-thread safe
- Folia region-aware

Designed for large networks,
not test servers.


SECURITY
===============================================================================

Sentinel is distributed as a protected binary.

- Multi-layer obfuscation
- Runtime integrity checks
- License-bound execution
- Anti-tamper & anti-debug logic

Decompilation produces noise, not answers.


TRANSPARENCY
===============================================================================

This repository exists for:
- Public presence
- Documentation surface
- Version visibility

It does NOT expose:
- Detection logic
- Thresholds
- Source code
- Bypass details

That information is intentionally private.


COMPATIBILITY
===============================================================================

- Minecraft Java 1.21.4+
- Paper / Folia
- Velocity (native support)
- Legitimate clients & mods


STATUS
===============================================================================

Active development.
Continuous research.
Silent updates.


FINAL NOTE
===============================================================================

If you are legitimate,
you will never notice Sentinel.

If you are not,
Sentinel has already noticed you.


© Sentinel Anti-Cheat
All rights reserved.
