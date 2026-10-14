# vet-clinic

**Is your pet sick?** This is where farmers using [Astra's PetOS](https://github.com/findastra/astras-pet-os) bring a
sick pet. Open a ticket, and other farmers help diagnose it and may offer a cure (a code fix).

*A public place of Astra's PetOS, by Astra.* Rules: [PET-PROGRAM-FRAMEWORK.md](https://github.com/findastra/astras-pet-os/blob/main/PET-PROGRAM-FRAMEWORK.md),
section 10, and [PROTECTION-RINGS.md](https://github.com/findastra/astras-pet-os/blob/main/PROTECTION-RINGS.md).

## Open a ticket

Use **New issue → Sick pet ticket**. Each ticket is `vet-clinic-ticket-<NNNN>` (its issue number), titled
`<pet-program>-v<version>: <what is wrong>`, for example `pet-program-12-v1.0: repo-catcher misses repos on D:`.

**Before you post, on your own PC:**
1. Attach only the sick tool's code and the error. Never your data.
2. Run name-eraser and a secret scan on everything you paste (no names, emails, paths with your user name, keys or tokens).
3. Private pets (health, finance, memes, privacy tools) describe the problem and the error only, never their code.
4. As your farm's L4 (the verified human who owns it), read the exact text before it goes out.

Everything here is public and stays public.

## Offer a cure

Use **New issue → Offer a cure** for an open ticket, or open a pull request against the pet's own repo and link it.
A cure is `vet-clinic-ticket-<NNNN>-cure-<N>`. Say what you changed, why, and how you tested it.

## ⚠️ Every community answer carries this warning

> **Unverified community answer.** This comes from someone you do not know. Do not run it as it is. If you want to try
> it, your farm puts it in quarantine, a checker agent reviews it, and you approve it first.

Trust tiers, highest first:
1. **Official:** signed releases from the maintainers.
2. **Kennel-verified:** reviewed and adopted through the Kennel.
3. **vet-clinic community:** everything here, always with the warning above.

## What happens to tickets

Every ticket, answer and cure stays logged here. Cures that work for many farms are reviewed by the maintainers and
become official patches, so community fixes improve Astra's PetOS for everyone.

**Who runs it:** the maintainer (Astra) moderates. A triage pet (pet-program-77, name to come) will label tickets,
check them for leaked secrets, and test offered cures in isolation. It never merges anything. Farms never connect to
each other; this repo is the only shared place.
