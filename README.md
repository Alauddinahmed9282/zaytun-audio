# Zaytun audio

Ayah-by-ayah Quran recitation files that the Zaytun app downloads.

- Reciter: Aaqib Azeez, from [Wikimedia Commons](https://commons.wikimedia.org/wiki/Category:Recitations_of_the_Qur%27an_by_Aaqib_Azeez).
- The whole-surah recordings were cut into one file per ayah (mono AAC).
- License: each surah keeps the license of its source file, either CC0 or
  [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/). The cut
  files of CC BY-SA surahs are shared under CC BY-SA 4.0 too. `sources.json`
  in each release lists the source file and license of every surah.

Each release asset `SSS.pack` holds one surah: `ZPK1`, the ayah count, the
size of each ayah (uint32 little-endian), then the m4a files in order.

Please don't delete or rename this repo: installed apps download from it.
