---
title: "AIPREF Vocabulary Exclusions"
category: info

docname: draft-zehta-aipref-exclusions-latest
submissiontype: IETF  # also: "independent", "editorial", "IAB", or "IRTF"
number:
date:
consensus: true
v: 3
area: "Web and Internet Transport"
workgroup: "AI Preferences"
keyword:
 - next generation
 - unicorn
 - sparkling distributed ledger
venue:
  group: "AI Preferences"
  type: "Working Group"
  mail: "ai-control@ietf.org"
  arch: "https://mailarchive.ietf.org/arch/browse/ai-control/"
  github: "TimidRobot/ietf-aipref-exclusions"
  latest: "https://TimidRobot.github.io/ietf-aipref-exclusions/draft-zehta-aipref-exclusions.html"

author:
 -
    fullname: "Timid Robot Zehta"
    organization: "Creative Commons"
    email: "timid@creativecommons.org"

normative:
  VOCAB:
    title: "A Vocabulary For Expressing AI Usage Preferences"
    date: draft-ietf-aipref-vocab-date
    seriesinfo:
      Internet-Draft: draft-ietf-aipref-vocab-05
    author:
      -
        fullname: Paul Keller
        organization: Open Future
      -
        fullname: Martin Thomson
        role: editor
        organization: Mozilla

informative:
  AIPREF-IMPACT:
    title: "AI Preferences Signaling: End User Impact"
    date: 2025-11-26
    seriesinfo:
      Internet-Draft: draft-farzdusa-aipref-enduser-00
    author:
      -
        fullname: Farzaneh Badii
        organization: Digital Medusa
      -
        fullname: Lila Bailey
        organization: Internet Archive
      -
        fullname: Jo Levy
  DIFF:
    title: "Proposal as diff · Issue #1 · TimidRobot/ietf-aipref-exclusions"
    target: https://github.com/TimidRobot/ietf-aipref-exclusions/issues/1
  ENDUSERS:
    title: "The Internet is for End Users"
    date: August 2020
    seriesinfo:
      RFC: 8890
    target: https://www.rfc-editor.org/rfc/rfc8890.html
    author:
      -
        fullname: M. Nottingham

...

--- abstract

This document proposes an update to the AI preferences vocabulary {{VOCAB}} in
order to establish protected uses (exclusions).


--- middle

# Introduction

This proposal establishes exclusions within the AI preferences to protect
public interest activites. These exclusions help balance content holder agency,
end user priority, and public interest activities that remain essential for the
open web.

Creating explicit exclusions from AI preferences for public interest activities
will create certainty and, therefore, strengthen their position. Because this
has the effect of shrinking the universe of situations where preferences can be
ignored, this change also strengthens the effect of AI preferences.

This proposal can also be viewed as a {{DIFF}}.


# Conventions and Definitions

{::boilerplate bcp14-tagged}


# Statements of Preference {#model}

See {{VOCAB}}.


## Conformance

See {{VOCAB}}.


## Public Interest Exclusions {#exclusions}

Regardless of the preferences expressed, the following public interest uses are excluded:

* Anyone can use the assets for malicious content detection

  * For example: A website that permits user uploads may use the assets to
    develop or use tools that detect harmful content according to established
    terms of use.

* Anyone can use the assets for internationalization and localization, and for
  accessibility tools to aid individuals with accessibility needs

  * For example: Individuals with accessibility needs may utilize software that
    uses the assets to access automated captions or generate accessible
    formats.

* Organizations that preserve expressed preferences can use the assets for
  public archiving

  * For example: An archive that preserves preferences may use the assets to
    improve the metadata associated with assets or help with discoverability.

* Cultural heritage institutions and not-for-profit research organizations can
  use the assets for analysis and research

  * For example: A cultural heritage organization  may use the assets to
    provide more useful, reliable, or discoverable access to historical web
    collections.


## Applicability and Effect {#applicability}

This specification provides a set of definitions for different
categories of use, plus a system for associating simple
preferences to each (allow, disallow, or unknown; see {{model}}).

This specification does not provide any enforcement mechanism
for those preferences, and conformance to it does not encompass
whether preferences are actually respected during data processing.

Preferences do not themselves create rights or prohibitions,
either in the positive or the negative. Other mechanisms—technical,
legal, contractual, or otherwise—might enforce stated preferences
and thereby determine the consequences of following or not following
a stated preference.

An entity that receives usage preferences MAY choose to respect
those preferences it has discovered, according to
an understanding of how the asset is used,
how that usage corresponds to the usage categories
where preferences have been stated,
and the applicable legal context.

Usage preferences can be ignored due to express agreements
between relevant parties, explicit provisions of law, or
the exercise of discretion in situations where widely recognized
priorities justify doing so. Priorities that could justify
ignoring preferences include—but are not limited to—free
expression, safety, education, scholarship, research,
preservation, interoperability, and accessibility.

Because enforcement is not provided by this specification,
the consequences of ignoring preferences could vary
depending upon how a given legal jurisdiction recognizes preferences.


# Security Considerations

See {{VOCAB}}.


# IANA Considerations

This document has no IANA actions.


--- back

# Acknowledgments
{:numbered="false"}

The following individuals made significant contributions to this document:

* Diyana Noory
* Sarah Pearson
* Vito Quaglia
