---
tags: [aksarans, index]
status: active
---

# Aksarans

Aksarans adalah **turn-based creature battler** di mana setiap creature merupakan manifestasi dari satu Aksara Jawa.

Core fantasy:

> Collect creature -> susun party 5 aksara -> baca keadaan battle -> rangkai 2-4 aksara menjadi satu aksi -> kuasai combo -> temukan Tembung tersembunyi -> evolve creature.

## Mulai dari sini

- [[01-Core/Game Vision]]
- [[01-Core/Core Loop]]
- [[01-Core/Design Principles]]
- [[01-Core/MVP Prototype]]
- [[02-Creatures/Creature System]]
- [[02-Creatures/Aksara Roster]]
- [[03-Battle/Battle Overview]]
- [[03-Battle/Combo System]]
- [[04-PvE/PvE Rules]]
- [[05-PvP/PvP Rules]]
- [[06-Progression/Progression Overview]]
- [[07-Tembung/Tembung System]]
- [[08-UX/Battle UX]]
- [[99-Design-Decisions/Open Questions]]

## Current design state

### Locked direction

- 20 base creatures: HA sampai NGA.
- Masing-masing punya Evolution I-III.
- Turn-based.
- Tidak ada explore/map pada core game.
- Player mengoleksi creature bertahap.
- Party membawa maksimal 5 creature.
- Satu aksi dapat merangkai maksimal 4 creature.
- Kombinasi tidak wajib menjadi kata Jawa.
- Tembung valid adalah advanced/mastery mechanic.
- PvE memakai informasi intent yang jelas untuk mengajarkan sistem.
- PvP memakai pemilihan aksi simultan agar tidak menjadi sekadar memilih counter setelah melihat jawaban lawan.

### Belum final

- Nilai damage/HP numerik.
- Ability final HA-...-NGA.
- Apakah party memakai shared HP atau HP individual.
- Detail partial telegraph PvP.
- Formula speed dan resolution.
- Sumber unlock creature final.
- Daftar Tembung yang digunakan.

> [!important]
> Angka di vault ini adalah contoh untuk menjelaskan sistem, bukan balancing final.
