# Make a useful job repeat

Run the job once. Review it. Correct it. Then schedule it. A prompt pasted into chat is not proof a schedule was created.

```text
Turn this approved workflow into a recurring task. First confirm the cadence, timezone, delivery destination, and what counts as a meaningful change. Use [schedule] in [timezone]. Keep it in this dedicated side chat if supported. Prefer cloud-accessible sources; tell me if it needs my computer awake. Update the same artifact if supported, otherwise make a dated replacement. Show the last successful run and keep earlier verified results if a source fails, clearly labeled as old. Deduplicate alerts and stay quiet when nothing meaningful changes, except report failures that prevent the job. Check for an existing routine before creating a duplicate. Show me the configuration, ask me to confirm it, then run one test. Show me how to pause or delete it.
```

## Verify it

- Open the routine or ask Muse to show its saved configuration.
- Confirm timezone, next run, destination, and source access.
- Inspect a test run in Activity and open its artifact.
- For cloud-only work, test a scheduled run with your laptop closed.
- Confirm how to pause it. Review cost and usage limits in your account.

## Change or stop it

```text
Show the routine for [job]. Change its cadence to [schedule], without creating a duplicate. Keep the same output and notification rules. Show the updated next run.
```

```text
Pause the routine for [job]. Confirm it is disabled and will not run again until I ask. Keep its existing artifact.
```
