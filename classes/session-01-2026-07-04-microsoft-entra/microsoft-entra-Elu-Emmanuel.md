# My Notes — [REPLACE WITH YOUR FULL NAME]

> **How to use this file:**
> 1. **Download** this file to your computer — click the **Raw** button on GitHub, then right-click and *Save As*, OR click the download icon at the top-right of the file view
> 2. **Rename** the downloaded file — replace `yourname` with your actual first and last name in lowercase, separated by hyphens, e.g. `microsoft-entra-oyimafu-emmanuel.md`
> 3. **Open** the renamed file in any text editor (Notepad, VS Code, TextEdit) and fill in your notes below
> 4. **Upload** your file to GitHub — go into this session folder on your forked repo, click **Add file → Upload files**, drag in your completed file, then click **Commit changes**
> 5. **Open a Pull Request** back to the main repo — the facilitator will review your notes before merging

---

## Key Concepts I Learned

<!-- Write the main ideas covered in today's session -->

-Securing access to resources using MS entra
-We focussed on authentication, MFA, CA and PIM  

---

## Lab / Hands-On Work

<!-- Describe what you did in the lab. Include steps, commands, or screenshots descriptions -->

### What I did
I enabled authentication policy needed for the platform (Microsoft authenticator, TAP and Email) 
I disabled authenticator policy not needed (SMS, Call, Fido etc).
Modified the lockout threshold, duration and created custom banned password.
I created a CA policy to require MFA, assigned it to all users, target all resources and from any location.
I created a CA policy to blocked MS admin portal, included all users and excluded the admin and break glass account, then I targeted the MS admin portals and configured the grant to block access and turned the policy to On.


### What happened / Result
All user were prompted to register for MFA on first login and to authenticate with MFA on future login.
User were prevented from accessing MS admin portal except for the Admin and breakglass account.

### Challenges I faced
The configs were successful. 
Could not practice PIM due to license limitation

---

## My Takeaways

<!-- What was most valuable to you personally from this session? -->
Ability to confidently establish a CA without hassle

---

## Questions I Still Have

<!-- Anything you want to follow up on or ask the mentor -->

-Need guide to create API plugins for agents
-

---

## Resources I Found Useful

<!-- Any links, docs, or Microsoft Learn modules you found helpful -->

-

---

*Submitted by: Elu Uchenna Emmanuel · eluemma*
