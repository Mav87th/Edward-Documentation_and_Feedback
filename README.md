# Edward — an automatic navigator for the DCS Mosquito

Edward is a mod for [DCS World](https://www.digitalcombatsimulator.com/) that gives the
de Havilland Mosquito F.B. Mk. VI the navigator it was built around. He reads the route, works the
fuel system, tunes the radios, calls the drift, and runs the bombing approach — from a radial menu
in the cockpit, opened with the `e` key.

Named after Edward Sismore, the RAF navigator who led the Mosquitos to Amiens prison in February
1944.

This repository holds the **documentation**, the **download**, and takes **bug reports and feature
requests**. The mod's source code lives elsewhere and is not public.

## Documentation

- **[Edward at a Glance](Edward_At_A_Glance.html)** — start here: what Edward does, one line per
  feature, where to start, and a clickable demonstration of the menu you can try in the browser
  without starting DCS.
- **[The Edward Menu](Edward_Menu_Overview.html)** — every wedge of the cockpit menu, what it
  does and what it shows, in full.
- **[Dead Reckoning Landmark Notes](DeadReckoning_Survey_Guide.html)** — the landmarks Edward calls
  out for dead reckoning, and how to add your own.
- **[Dead Reckoning — The Navigator's Calls](DeadReckoning_Rules.html)** — the full rules: how
  Edward chooses the landmarks along your route, and when, how and why he calls them in the air.

The last three are written in the manner of a wartime Air Publication, which felt like the right register for
an aeroplane of this vintage.

## Reporting a bug or asking for something

There are two forms (a free GitHub account is needed to send either):

- **[Report a bug](https://github.com/Mav87th/Edward-Documentation_and_Feedback/issues/new?template=bug_report.yml)** — something not working
- **[Request a feature](https://github.com/Mav87th/Edward-Documentation_and_Feedback/issues/new?template=feature_request.yml)** — an idea

Or see [all open issues](https://github.com/Mav87th/Edward-Documentation_and_Feedback/issues) first, in
case it has already been reported.

What helps most in a bug report:

- what you expected, and what happened instead
- which mission and which aircraft
- your `dcs.log`, or the part of it mentioning `EDWARD` — it is in
  `Saved Games\<your DCS folder>\Logs\dcs.log`
- whether it happens every time or only sometimes

Screenshots are welcome. A rough report is far better than no report, so do not hold one back for
lack of detail.

## Status

**Edward is not available to download yet.** When it is released, the download
(`Edward_Mod_Files.zip`) will be on this repository's
[Releases page](https://github.com/Mav87th/Edward-Documentation_and_Feedback/releases), and also on
the [DCS World User Files](https://www.digitalcombatsimulator.com/en/files/). The documentation is
here so the mod can be read about and discussed while it is finished.

The download will include `INSTALL_GUIDE.txt`, with the install steps and how to fly Edward in
multiplayer.

Edward works when you host a game and when you join one, as long as the server allows aircraft data
export. Some servers switch it off (the server setting "Allow player export"). Edward cannot see your
aircraft there, so he switches himself off for that flight and tells you so when you get into the
cockpit.

Edward is in active development and is not finished. Things move, and some of what is described in
the documentation has been tested more thoroughly than the rest — where that matters, the guides say
so rather than leaving you to find out in the air.
