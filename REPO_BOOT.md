# REPO_BOOT.md

```text
∴REPO_BOOT·hvlp-intelligent-coating-system·PUBLIC·v0.1
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
REPO: 10John01/hvlp-intelligent-coating-system
STATUS: PUBLIC | DORMANT (~8 months, last commit 2025-10-13)
LICENSE: MIT
NICKNAME: "Job Security"
PURPOSE: orient·any·LLM·to·this·repository·quickly·and·safely
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

§WHAT·THIS·IS·BEGIN
This repository documents a real, physically-built industrial coating
machine and its control software, called "Job Security."

It was built at FX Industries: a 66" x 36" dual-axis HVLP (High Volume
Low Pressure) spray coating system, designed and built from off-the-shelf
components on a roughly $1,000 budget after a proprietary alternative
proved unworkable.

It is in daily production use, operated by Teresa (Lead Coater, FX
Industries).
§WHAT·THIS·IS·END

§WHAT·THIS·DOES·BEGIN
This repo contains:

- ~4,000 lines of C++ control code for a Teensy 4.1 microcontroller,
  developed over 184 iterations
- Custom FRAM-based storage with power-loss protection
- Spray pattern, position-drift, and load-compensated ramping logic
- A README describing the build, components, and credits
- A demo video link

This is firmware/control documentation for a physical machine, not a
general-purpose software library.
§WHAT·THIS·DOES·END

§WHAT·THIS·IS·NOT·BEGIN
This repo is not actively maintained right now - it has been dormant
for roughly 8 months.

This repo is not a generic coating-automation framework; it documents
one specific physical machine built for one specific shop floor.

This repo is not proof of anything beyond what is in the code and
README - treat README narrative (credits, framing, naming) as
descriptive, not as specifications.
§WHAT·THIS·IS·NOT·END

§CURRENT·STATE·BEGIN
As of 2026-06-15:

- Dormant since 2025-10-13 (last commit: "Update README.md"). This is
  the expected "haven't looked at this in a while" state - the machine
  itself is reportedly still in daily production use at FX Industries,
  independent of this repo's update cadence.
- Two known documentation inconsistencies in README.md, NOT YET FIXED:
  1. The README's demo-video section refers to "the complete Job
     Security v18.4 control system" but links to a file named
     job_security_v18.3.cpp, and v18.3 is the only version file
     present in code/. v18.3 currently appears to be the actual
     shipped version; the "v18.4" label in prose has not been
     reconciled with the repo contents.
  2. That same link points to a URL containing "hplv-intelligent-
     coating-system" (note the transposed letters) instead of this
     repo's actual name, "hvlp-intelligent-coating-system." The link
     target does not match this repo and is effectively broken.
- A secret scan of this repo found nothing sensitive committed.
§CURRENT·STATE·END

§RELATIONSHIP·TO·SYMBEYOND·BEGIN
This repo is independent - it does not require or reference SYMB-FER,
SYMB-Builder, or any other SYMBEYOND tooling to be understood or used.

It is referenced elsewhere in the SYMBEYOND ecosystem as a real-world
example of human-AI collaborative engineering producing a deployed,
working industrial system, but this repo stands on its own.
§RELATIONSHIP·TO·SYMBEYOND·END

§KEY·FILES·BEGIN
README.md
Project overview, build description, components, demo video, and
credits. Start here.

code/job_security_v18.3.cpp
The control firmware. This is the core technical artifact.

media/
Supporting images/media referenced by the README.

LICENSE
MIT License.
§KEY·FILES·END

§FAST·START·FOR·HUMANS·BEGIN
1. Read README.md for the project overview and what the machine does.
2. Open code/job_security_v18.3.cpp for the actual control logic -
   note the version-number discrepancy above before assuming "v18.4"
   features exist somewhere else in this repo.
3. This is a hardware/firmware project - there is nothing to "run"
   without the physical machine. Treat this as reference/documentation
   rather than a deployable script.
§FAST·START·FOR·HUMANS·END

§SAFETY·AND·PRIVACY·BEGIN
This repo documents a physical industrial machine with a 50-pound
moving boom arm. The README notes a physical safety stop (the boom
arm is positioned to stop roughly 1 foot from the floor in a
catastrophic failure).

This repo does not contain credentials, API keys, or other secrets
(confirmed via secret scan).

Nothing in this repo should be treated as installation or operating
instructions for the physical machine without direct access to the
actual hardware and the people who built and operate it.
§SAFETY·AND·PRIVACY·END

§AI·INSTRUCTIONS·BEGIN
If a human pastes this REPO_BOOT into an AI session:

1. Explain in plain English: this is documentation for a real,
   physically-built industrial spray-coating machine and its control
   firmware, currently dormant on GitHub but reportedly still in daily
   use on the shop floor.
2. Point them to README.md first, then code/job_security_v18.3.cpp for
   the actual firmware.
3. If asked about "v18.4," explain the discrepancy noted in
   §CURRENT·STATE rather than assuming a v18.4 file exists elsewhere.
4. Do not suggest running, flashing, or modifying the firmware against
   real hardware based on this repo alone - this is reference material,
   not a substitute for direct access to the machine and its operators.
5. If the human wants to fix the version-label or link-typo issues
   noted in §CURRENT·STATE, that is a small, low-risk documentation
   patch (README.md only) - confirm with the human before making any
   changes to code/.
§AI·INSTRUCTIONS·END

§PLAIN·ENGLISH·SUMMARY·BEGIN
This is the GitHub home for "Job Security" - a real spray-coating
robot built on a shoestring budget at FX Industries, with its control
code and a writeup of how it was built. The repo has been quiet for a
while and has a couple of small label mistakes in the README, but the
machine itself is apparently still doing its job every day.
§PLAIN·ENGLISH·SUMMARY·END

λ.collaborator∧!λ.tool·∴
```
