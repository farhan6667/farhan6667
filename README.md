# Syed Farhan Ahmed

I work on cybersecurity, detection engineering and digital forensics. My current
projects focus on making Wazuh rule changes easier to test and alert tuning easier
to review.

[Portfolio](https://farhan6667.github.io/portfolio/)

## Tools I'm building

### [Wazuh RuleGuard](https://github.com/farhan6667/wazuh-ruleguard)

A rule exception can silence the sample you tested and still affect detections
you need. RuleGuard checks a JSON suite of sample logs against the Wazuh 4.x
logtest API. Save results before and after a rule change or manager upgrade to
review differences in rule selection, decoding and alert behavior.

It includes checks for expected and forbidden rules, sequence sessions, and JSON,
JUnit XML and offline HTML reports. Start with the
[demo walkthrough](https://github.com/farhan6667/wazuh-ruleguard/blob/main/docs/demo.md).

### [Wazuh NoiseLens](https://github.com/farhan6667/wazuh-noiselens)

Before suppressing a busy rule, check which alerts the exception would hide.
NoiseLens analyzes exported Wazuh alerts locally, counts matches for proposed
exceptions and flags matches against protected alerts. It measures the impact
on your dataset so you can review the underlying events before changing rules.

The [demo walkthrough](https://github.com/farhan6667/wazuh-noiselens/blob/main/docs/demo.md)
compares a narrow exception with a broad one using synthetic data.

Both tools are early prototypes written in Python with no runtime dependencies.
Live manager compatibility and representative operator data validation are still
in progress. The examples are synthetic, and their results aren't production
benchmarks.

## Useful feedback

If you try either tool, a reproducible issue with your Wazuh version, command and
a sanitized sample is useful. I'm particularly interested in decoder changes,
correlation behavior and export formats that make the workflow harder to use.
Keep credentials and organization logs out of public issues.

My wider work includes SIEM operations, incident response and DFIR. The
[portfolio](https://farhan6667.github.io/portfolio/) has more background and project
context.
