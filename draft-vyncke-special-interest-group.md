---
title: IETF Special Interest Group Guidelines
abbrev: SIG
docname: draft-vyncke-special-interest-group
date:
category: bcp

ipr: trust200902
keyword: Internet-Draft

stand_alone: yes
pi: [toc, sortrefs, symrefs]
updates: RFC2418

author:
  -
    ins: E. Vyncke
    name: Éric Vyncke
    org: Cisco
    country: Belgium
    email: evyncke@cisco.com

normative:
  RFC2418:
informative:

--- abstract
This document describes the guidelines for the formation and operation of a special kind of Working Group (WG): Special Interest Group (SIG). SIGs differ from WG because their purpose is not to publish protocol or process; they are rather a place where discussion on existing IETF technologies can take place.

This document updates RFC2418.

--- middle

# Introduction

Unofficial side meetings exist since at least IETF 99 and are quite useful and successful with a wide variety of topics. But, they are non-official and they do not appear on the IETF meeting agenda, only on a side wiki page. They are sometimes also a one time meeting, no continuity.

There is a desire for some IETF members sharing the same interest in an IETF technology to discuss an already specified and deployed technology, mainly but not limited to operations. The discussion could also include sharing experience in training, in glossaries, in how different technologies could interact, ...

This document describes the guidelines for the formation and operation of a special kind of Working Group (WG): Special Interest Group (SIG). SIGs differ from WG because their purpose is not to publish protocol or process; they are rather a place where discussion on existing IETF technologies can take place.

The formation of SIG is similar to the normal {{RFC2418}} WG: one birds of feather (BoF) discussion within an area, Internet Engineering Steering Group (IESG) approval; the SIG operation is also similar with mailing list, data tracker to maintain the list of adopted and individual documents. SIG MAY have no milestone.

SIGs are terminated at the discretion of their Area Director (AD) who should review annually with the IESG and the SIG WG chairs whether the SIG should continue or be terminated.

This document is based on the experience gained with the formation and operation of the Media Operations (MOPS) Working Group in 2019.

# Terminology
{::boilerplate bcp14}

# Modification of RFC 2418 for SIG

{{RFC2418}} provides guidelines for the formation and operation of WG that are not fully in line with the SIG. This section documents the differences.

## SIG Formation

### Criteria for formation
When determining whether it is appropriate to create a special interest group, the Area Director(s) and the IESG will consider the same issues as in setion 2.1 of {{RFC2418}} at the exception of "Are the goals specific and reasonably achievable, and achievable within a reasonable time frame?". The reasoning is that SIG do not have goals, i.e., no protocols or processes will be designed.

### Charter
A SIG MUST have a charter that is negotiated between a prospective working group Chair and the relevant Area Director(s), although final approval is made by the IESG with advice from the Internet Architecture Board (IAB).

The elements of section 2.2 of {{RFC2418}} are all applicable at the exception of the milestones. Milestones are OPTIONAL for SIG. Section 2.3 of {{RFC2418}} fully applies to SIG (charter review & approval).

Experience with the MOPS WG has shown that SIG will probably be in the Operation Area but the responsible Area Director MAY be different than the Operation Area Director. As SIG may cover multiple areas, it is expected that there will be several technical advisors.

### Birds of a feather
The section 2.4 of {{RFC2418}} is applicable to SIG: BoF are also an instrument for the community to judge whether there is interest to create a SIG.

## SIG Operation

Section 3 of {{RFC2418}} applies for SIG: with mailing list discussions but it is expected that the value of SIG will be in the interim and plenary meetings. 

A SIG differs from {{RFC2418}}

# Security Considerations
Documents describing IETF processes, such as this one, do not have an impact on the security of the network infrastructure or of Internet applications.

# IANA Considerations

# Acknowledgements
This revision of this document is based on IESG discussions that happened during the creation of the MOPS Working Group with Leslie Daigle, Glenn Deen, Barry Leiba, and Warren Kumari.