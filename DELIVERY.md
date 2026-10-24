# RHL project homepage — review delivery

Prepared on 24 October 2026 from manuscript v0.31 and the selected historical experiment records. This is a local review build and a static GitHub Pages package. It is now hosted for author review at https://jarvisjws.github.io/rhl-project-page/. The source repository remains private; the website is publicly accessible. Final author acceptance is still pending.

## Open and review

Open `index.html` in a browser. All case content, videos and recorded-phase captions work offline. An optional local HTTP launcher is included beside the `site` directory in the delivery archive. The same static files use relative paths suitable for a GitHub Pages project site.

The page contains the abstract, three method figures, the combined benchmark-level results, eight RoboTwin cases, eleven RoboDojo cases and four selected xylophone runs. The first screen presents two complete recorded segments rather than a montage that omits the transitions. Players offer native full-screen controls, replay, speed selection and recorded-event jumps. The xylophone pairs support play-from-start and pause together; independent runs are not forced into an artificial common timeline.

## What is delivered

| Material | Delivered presentation |
|---|---|
| RoboTwin, 8 cases | Original policy initial/failure state views and complete available recovery segments |
| RoboDojo, 10 cases | Full sampled measured-state visualizations, with first and terminal states retained |
| RoboDojo swap blocks, L2/seed0 | 84 discrete recorded events, explicitly labeled; the separate initial-state image is preserved |
| Xylophone mechanism | L1 runs 52/55, later L14/62 and L11/60; two original successes and two original failures |
| Media files | 23 primary segments plus 2 auxiliary original-camera recordings: 25 MP4 files in total |
| Source accounting | Relative media links, original run identities, file hashes, native goal fields and exact step mappings in `assets/media-sources.json` and its timing sidecars |

The 25 files comprise eight original recovery recordings, sixteen measured-state reconstructions and one discrete-event sequence. No new task-solving trial was run. Creating the Dojo visualizations initializes the original environment, then restores historical states without advancing physics between them. Rendering does not provide new task-success or physical-qualification evidence.

## Historical media gaps retained

1. **Eight Twin policy videos:** inspected action traces record joint drive targets rather than complete measured articulation states; some also lack complete object orientations. They cannot support an honest continuous third-person reconstruction. Verified initial and selected failure states are shown instead. The original recovery starts remain distinct from the source policy failures.
2. **Swap blocks continuous motion:** the button articulation is present only at sparse recorded events. The event sequence begins at step 200 and ends at step 13015, showing two events per display second. Its 42-second media duration is not the elapsed simulation time. The verified step-1 starting state appears separately; missing motion is not interpolated.
3. **Source framing:** handover 3032 and dual bottles 48 use expanded, fixed external observer views reconstructed from their original scene records. Their original-camera recordings remain available as auxiliary downloads. No picture-in-picture panels are used.

These are recording-coverage limits, not judgments that the tasks were initially impossible. Ordinary failures have not been reclassified as irrecoverable.

## Evidence and interpretation

The outcome figures remain 104/115 eligible Twin cases, with 104/121 shown before the six historical human scope exclusions, and 620/627 for the fixed Dojo batch. The website does not introduce a new denominator or count these selected videos as independent benchmark samples. Four xylophone runs are not four distinct task identities: two are different attempts on L1.

Videos show recording/simulation time and exclude model inference, diagnosis and planning latency. Dense Dojo views sample every tenth 250 Hz state at 25 display frames/s, retaining endpoint states; exact times are given by the step maps. Xylophone runs 52 and 55 are not consecutive. The retained-rule record of 19 successes in 24 previously failed layouts is shown with its five failures and expanded-horizon boundary, not as a controlled efficiency or unseen-task transfer claim.

Basic checks covered complete decoding and actual frame counts for all 25 files, source preservation and state readbacks, actual browser playback for all 19 case players and all four mechanism players, captions, paired controls, event seeking, speed selection, image enlargement and a 390-pixel mobile viewport. These checks do not replace the author's judgment of presentation quality.

## Before public release

The review URL is established. Review the page and settle the author list, publication/citation metadata, Paper/Code links and the target venue's anonymity requirements before final release. `ATTRIBUTION.md` preserves inspected environment code-license notices; these do not automatically license every third-party mesh or texture. Confirm the selected media's public redistribution scope before publishing.

Copy only the approved `site` contents to the public homepage repository. The companion GitHub Pages workflow is manual-only and has not been installed or triggered. Do not publish the private project repository, experiment archives or internal evidence paths. Public release and overall paper acceptance remain separate from this local delivery.

## 24 October provenance clarification

The result explanation explicitly retains author-reviewed task-goal acceptance for Twin Pick49 and Handover3028, without overwriting the original framework checks. Counts and all media remain unchanged. The r2 review archive supersedes the first archive for current wording; the review website is now hosted, while the final research release remains pending.
