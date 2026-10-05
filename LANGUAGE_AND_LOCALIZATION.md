# AI Hotel — Language and Localization

## Launch languages

AI Hotel is designed from the beginning for:
- English;
- Russian.

## Architecture rule

English and Russian must use the same canonical intent, capability, policy and action model.

Localization should change:
- wording;
- tone;
- language;
- local formatting where required.

Localization should not silently create different operational rules.

## Guest experience

The guest should be able to make the same request naturally in either language.

Examples:

English:
> Please move housekeeping until after 2 PM and ask for late checkout.

Russian:
> Перенеси уборку после 14:00 и узнай, можно ли сделать поздний выезд.

Both should map to the same structured hotel actions and verification states.

## Critical messages

Extra care is required for:
- payment confirmation;
- cancellation;
- reservation modification;
- consent;
- security;
- safety;
- unavailable services;
- failed actions.

Meaning must remain consistent across languages.

## Repository language

Public and technical repository documentation is maintained in English to support international development and collaboration.

## Property validation

English and Russian are product design priorities, not a claim about any hotel's guest-language mix. Confirm the required languages, including Arabic where relevant, with each property before a live pilot.

Use the same approved policies across languages, and evaluate whether quantities, timing, eligibility and promises retain the same meaning. If reliable language support or policy content is unavailable, route to staff.
