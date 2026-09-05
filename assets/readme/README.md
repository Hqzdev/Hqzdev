# Profile visual sources

## Story

Audience: engineering teams, founders and potential collaborators.

Positioning: Team Lead & Entrepreneur, as requested by the profile owner. The narrative connects product direction, technical decisions and team execution. It makes no claims about team size, revenue, funding or customer numbers.

Proof: selected public projects and concrete implementation choices, followed by a dated snapshot of public GitHub data. The first action is to inspect a project or contact the author.

## Visual direction

Palette: background `#080808`, surface `#141414`, foreground `#f5f5f5`, secondary `#a3a3a3`, rules `#333333`. All authored colors are neutral grayscale.

Typography: system sans-serif for headlines and diagram labels; system monospace for identity and metadata. No remote fonts.

Geometry: an 8-unit spacing grid, thin rules, restrained radii and generous margins. The recurring motif is a trace connecting inputs, system boundaries and outcomes.

Composition: identity and a Tether execution specimen; a leadership table; project flows and implementation details; two measured charts; a contact panel.

## Asset provenance

| Asset | Source |
| --- | --- |
| `hero.svg` | Existing md.local identity, the owner's requested role, and Tether's capture / inspect / replay model. |
| `project-flows.svg` | Public READMEs and selected implementation files in Tether, Slate, Grounded and Pilot Agent; Metrix's architecture from the existing profile. |
| `activity.svg` | Weekly sums from the unauthenticated public GitHub contribution calendar, 7 June–5 September 2026. |
| `languages.svg` | GitHub's primary language for each public non-fork repository, captured 6 September 2026. |
| `contact.svg` | The requested leadership and entrepreneurship positioning; existing profile contact links. |
| `github-snapshot.json` | Public source URLs, daily counts, weekly totals and repository language records used for both charts. |

## Project evidence

Reviewed on 6 September 2026. This is a profile content review, not a production certification or a fresh execution of every project's tests.

- **Tether:** [README](https://github.com/Hqzdev/Tether#readme), [replay endpoints](https://github.com/Hqzdev/Tether/blob/main/core/proxy/src/trace/replay.rs), [SQLite response cache and tests](https://github.com/Hqzdev/Tether/blob/main/core/proxy/crates/tether-cache/src/lib.rs).
- **Slate:** [README](https://github.com/Hqzdev/Slate#readme), [room persistence](https://github.com/Hqzdev/Slate/blob/main/services/sync/src/roomPersistence.js), [AI action tests](https://github.com/Hqzdev/Slate/blob/main/apps/web/tests/aiActionExecutor.test.ts), [execution worker](https://github.com/Hqzdev/Slate/blob/main/services/execution/src/worker.js).
- **Grounded:** [README](https://github.com/Hqzdev/Grounded#readme), [retrieval service](https://github.com/Hqzdev/Grounded/blob/main/services/retrieval/app/services.py), [ingestion and retrieval smoke script](https://github.com/Hqzdev/Grounded/blob/main/scripts/smoke-ingestion-retrieval.sh).
- **Pilot Agent:** [README](https://github.com/Hqzdev/pilot-agent#readme), [iteration budget](https://github.com/Hqzdev/pilot-agent/blob/main/pilot_agent/agent/iteration_budget.py), [runtime tests](https://github.com/Hqzdev/pilot-agent/blob/main/tests/test_runtime_hardening.py).
- **Metrix:** [repository](https://github.com/Hqzdev/Metrix), [website](https://metrixplatform.vercel.app), and its technical description in the previous version of this profile. Development status is retained.

## Chart definitions

Activity counts use GitHub's contribution definitions. They describe the public calendar and do not measure productivity. Each bar represents one seven-day period, starting on the labeled date. The chart uses a zero baseline and a maximum axis value of 100 contributions.

Language bars count repositories, not bytes, proficiency or time spent. The Other group contains C#, Dart, Go and Rust. Three repositories have no detected primary language and are explicitly excluded from the language bars. The dataset includes 50 public non-fork repositories, of which 47 have a detected language.

All graphics are static and self-contained: no scripts, external images, web fonts, animation or `foreignObject`. The complete project descriptions and chart totals remain available as selectable Markdown. Opaque backgrounds preserve the intended appearance on both GitHub themes.
