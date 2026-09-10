# Tahsin Sakin

Information Systems Engineer · Ankara  
[LinkedIn](https://www.linkedin.com/in/tahsin-sakin-390961199) · [BudVia](https://tahsinsakin.github.io/belvia/) · [source](https://github.com/tahsinsakin/belvia)

I design and ship small systems. I start from the constraint, not from the stack. If the work can stay on the device, it stays on the device. If a service is not earning its keep, it does not ship.

---

## Selected work

### [BudVia](https://github.com/tahsinsakin/belvia)
On-device itinerary for trips booked across several apps.

Cheap travel splits a week across Wizz, FlixBus, Airbnb, Booking, and whatever else sold the cheapest piece. Each confirmation is fine on its own. The trip is not. BudVia is the layer that holds the plan those apps do not hold together.

It does not sell tickets. It does not replace the booking apps. A tap opens the app the ticket was bought in. Times, dates, routes, and the bag sit in one place. There is no account and no server. Clearing the trip deletes the only copy.

| | |
|---|---|
| Live | [tahsinsakin.github.io/belvia](https://tahsinsakin.github.io/belvia/) |
| Repo | [tahsinsakin/belvia](https://github.com/tahsinsakin/belvia) |
| Form | PWA now, Expo / React Native in `mobile/` |
| Data | `localStorage` key `belvia-v2` |
| License | MIT |

**Decisions that matter**

- Local-first. The itinerary never leaves the phone.
- Deep links over a new booking backend.
- System maps instead of a tile API.
- Dated schedule, not a list of times without days.
- Sample itinerary is masked. Live booking codes stay out of the repo.

Safari → Share → Add to Home Screen.

---

## How I work

| Preference | Practice |
|---|---|
| Scope | One job per product. BudVia remembers the trip. It does not sell the trip. |
| Surface | TypeScript, Expo, React Native, static web |
| Storage | On-device unless a server is the product |
| Interface | Fewer screens. The next action is visible. |
| Review | If it needs an account to demo, the design is unfinished |

```
TypeScript · JavaScript · React · Expo · HTML/CSS · Git
```

---

## Background

Ankara Bilim University — Information Systems Engineering.

Training is split across software and the systems that software sits on. That is the lens: how a thing is assembled, and where it fails when the extra parts are removed.

---

## Contact

Work correspondence: [linkedin.com/in/tahsin-sakin-390961199](https://www.linkedin.com/in/tahsin-sakin-390961199)
