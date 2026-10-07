# NexaMed-Medecin-Releases

Depot de releases Velopack du poste **NexaMed Medecin** (packId : com.scilicode.nexamed.medecin).

Alimente par le workflow `release-velopack.yml` du depot source `scilicode-sys/NexaMed` : ne rien modifier ici a la main.
Les `Setup.exe`, `.nupkg` et `releases.<canal>.json` sont regeneres a chaque course. Le poste lit ce depot par son URL absolue
(`MiseAJourVelopack.NexaMed-Medecin-Releases`), et le jeton qui y ecrit ne couvre que lui.
