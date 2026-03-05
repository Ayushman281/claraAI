# Changelog — account_e2e_full

**Generated:** 2026-03-05T09:18:25Z
**Account:** TestCo Fire Protection

## Summary

- Version: v1 (demo) → v2 (post-onboarding)
- Total memo field changes: 11
- Total spec field changes: 10
- Conflicts resolved: 0

## Account Memo Changes

- **CHANGED** `call_transfer_rules.business_hours_transfer_number`
  - Before: `None`
  - After:  `512-555-0150`
- **CHANGED** `call_transfer_rules.transfer_timeout_seconds`
  - Before: `None`
  - After:  `30`
- **CHANGED** `emergency_definition`
  - Before: `['Active sprinkler discharge', 'Fire suppression system discharge', 'Fire alarm actively going off']`
  - After:  `['Active sprinkler discharge', 'Fire suppression system discharge', 'Fire alarm actively going off', 'CO detector / carbon monoxide alarm activation']`
- **CHANGED** `emergency_routing_rules.primary_transfer_number`
  - Before: `None`
  - After:  `512-555-0100`
- **CHANGED** `emergency_routing_rules.secondary_transfer_number`
  - Before: `None`
  - After:  `512-555-0199`
- **CHANGED** `emergency_routing_rules.transfer_timeout_seconds`
  - Before: `None`
  - After:  `30`
- **CHANGED** `integration_constraints`
  - Before: `['Never mention ServiceTrade to callers — internal use only']`
  - After:  `['Never mention ServiceTrade to callers — internal use only', 'Do not create sprinkler jobs in ServiceTrade from field techs']`
- **CHANGED** `notes`
  - Before: `Extracted via rule-based engine from transcript. Source: demo call.`
  - After:  `Extracted via rule-based engine from transcript. Source: demo call. | Updated from onboarding call on 2026-03-05. 0 field(s) updated.`
- **CHANGED** `questions_or_unknowns`
  - Before: `['Emergency on-call primary phone number not specified', 'Transfer timeout/retry settings not specified', 'Business hours main transfer number not specified']`
  - After:  `[]`
- **CHANGED** `services_supported`
  - Before: `['Sprinkler System', 'Fire Suppression', 'Fire Alarm']`
  - After:  `['Sprinkler System', 'Fire Suppression', 'Fire Alarm', 'Co Detector']`
- **CHANGED** `version`
  - Before: `v1`
  - After:  `v2`

## Agent Spec Changes

- **CHANGED** `call_transfer_protocol.business_hours.timeout_seconds`
  - Before: `None`
  - After:  `30`
- **CHANGED** `call_transfer_protocol.business_hours.transfer_number`
  - Before: `None`
  - After:  `512-555-0150`
- **CHANGED** `call_transfer_protocol.emergency_after_hours.primary_transfer_number`
  - Before: `None`
  - After:  `512-555-0100`
- **CHANGED** `call_transfer_protocol.emergency_after_hours.secondary_transfer_number`
  - Before: `None`
  - After:  `512-555-0199`
- **CHANGED** `call_transfer_protocol.emergency_after_hours.timeout_seconds`
  - Before: `None`
  - After:  `30`
- **CHANGED** `key_variables.business_hours_transfer_number`
  - Before: `None`
  - After:  `512-555-0150`
- **CHANGED** `key_variables.emergency_routing_primary`
  - Before: `None`
  - After:  `512-555-0100`
- **CHANGED** `key_variables.emergency_routing_secondary`
  - Before: `None`
  - After:  `512-555-0199`
- **CHANGED** `key_variables.emergency_transfer_timeout_seconds`
  - Before: `None`
  - After:  `30`
- **CHANGED** `version`
  - Before: `v1`
  - After:  `v2`

## Remaining Open Questions

_All questions resolved._