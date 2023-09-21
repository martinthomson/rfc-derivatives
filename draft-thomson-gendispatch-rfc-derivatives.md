---
title: "Request to the Trustees of the IETF Trust to Permit the Creation of Derivative Works"
abbrev: "RFC Derivative Works"
category: info

docname: draft-thomson-gendispatch-rfc-derivatives-latest
submissiontype: IETF  # also: "independent", "editorial", "IAB", or "IRTF"
number:
date:
consensus: true
v: 3
area: "General"
workgroup: "General Area Dispatch"
keyword:
 - license
 - monopoly
updates: 5377
venue:
  group: "General Area Dispatch"
  type: "Working Group"
  mail: "gendispatch@ietf.org"
  arch: "https://mailarchive.ietf.org/arch/browse/gendispatch/"
  github: "martinthomson/rfc-derivatives"
  latest: "https://martinthomson.github.io/rfc-derivatives/draft-thomson-gendispatch-rfc-derivatives.html"

author:
 -
    fullname: Martin Thomson
    organization: Mozilla
    email: mt@lowentropy.net
    country: AU

normative:
  LICENSE:
    title: "Trust Legal Provisions (TLP)"
    target: "https://trustee.ietf.org/documents/trust-legal-provisions/"
    author:
      - org: IETF Trust
    seriesinfo:
      Revision: 5.0
    date: 2015-03-25

informative:


--- abstract

The IETF Trust holds rights to RFCs.  This document updates RFC 5377 to request
that the IETF Trust change its licensing for IETF documents to permit the
creation of derivative works.


--- middle

# Introduction

The IETF produces RFCs to further its mission {{?RFC3935}} of improving the
Internet.  Intellectual property rights for these documents are held by the IETF
Trust {{?BCP101}}.

Previous advice to the IETF Trust advised that usage rights for IETF documents
be limited to copying and translations.  This can have the effect of granting
the IETF monopoly rights over the maintenance of work that is published in IETF
documents.

This document revises the advice to the IETF Trust given in RFC 5377
{{!ADVICE=RFC5377}} to expand the rights granted in relation to IETF documents
to include the ability to create derivative works.

The IETF Trust, by way of its Trustees, has indicated that it will respect the
wishes of the IETF in regard to the rights it will grant in relation to RFCs.
It is therefore the IETF's responsibility to articulate those wishes.


# Rationale

The mission of the IETF {{!RFC3935}} is to make the Internet better.  This is
primarily achieved by producing documents, RFCs, that define interoperable
Internet protocols.  The IETF also publishes RFCs that further this mission in
other ways, including Best Current Practice (BCP), Informational, and
Experimental documents.

Over time, the IETF has published documents on a very wide range of topics.  The
quality of IETF publications depends on the ability for the IETF to find a
sufficient number of participants with expertise in the topic area.

The IETF has an excellent reputation as a venue for the standardization of
Internet protocols.  The protocols and documents produced by the IETF are well
respected.  The IETF enjoys strong ongoing support and so appears to be a good
choice of venue for standardization in the areas in which the community has
strong expertise.

Should the IETF be unable to attract adequate depth of expertise to produce a
revision of existing work, another organization might have that expertise.  In
the most extreme case, the IETF could fail entirely or cease to be a viable
venue for standardization, making it necessary to produce revisions in another
venue.  Licensing that permits the creation of derivative works could allow
another organization to perform necessary maintenance or revisions.

The licensing terms generated in response to RFC 5377 {{!ADVICE=RFC5377}} do not
permit the creation of derivative works.  This could unduly give the IETF an
monopoly over the maintenance of protocols that are published as IETF documents.

While contributors are able to provide a license for this purpose, that depends
on securing permission from all contributors.  The collaborative nature of IETF
work makes it difficult to obtain this sort of license.  The IETF Trust is in a
position to make more permissive terms more readily available.

Similar considerations apply to other document streams: IAB, IRTF, or
independent submissions {{?RFC4844}}; however, see {{other}}.


# Permitting the Creation of Derivative Works

This document advises the IETF Trust to amend the license for IETF Documents
(RFCs and Internet-Drafts) {{LICENSE}} to permit the creation of derivative
works.

This is in addition to the rights granted under the existing license
{{LICENSE}}.


## Recognition of Status {#status}

The IETF Trust is requested to ensure that any license permitting the creation
of a derivative work stipulates that the original work be clearly identified.
Derivatives also need to clearly attribute authors and contributors of the
original.


## Withholding of Naming Rights {#naming}

The IETF Trust is advised to make the license to create derivative works subject
to the use of a distinct protocol name when creating new versions of existing
protocols.  This need not apply to reused or copied protocol elements or fields;
it only applies to the protocol, extension, or component that is being revised.
The IETF Trust should maintain the ability to permit the reuse of a name in
appropriate cases, such as when the IETF agrees to transfer development of
a protocol to a different organization or where the IETF has decided not
to take up a given piece of work and the proponents bring it elsewhere.

The potential for confusion about the status of a derivative work is not
completely avoidable.  However, the requirement to use a new name for protocols
or mechanisms ensures that names are not used to compound any potential
confusion.


# Other Streams {#other}

The IETF Trust is also responsible for licensing terms on documents that are
produced in relation to the activity of other RFC streams (IRTF, IAB, and
independent).  The IETF cannot advise the IETF Trust as it relates to licenses
on RFCs published in these other streams.

Ideally, other streams would adopt the amended license terms, as they have done
for the existing license {{LICENSE}}.  That would ensure consistency across the
RFC series and for work contributed to other streams.  However, this document
cannot serve as advice from other streams; it can only capture IETF consensus.


# Older RFCs {#old}

As noted in {{LICENSE}}, IETF documents published prior to the effective date of
that license are subject to other licensing provisions.  The IETF Trust is not
requested to attempt to secure the ability to alter the license terms for these
documents.


# Security Considerations

This document is purely procedural in nature and therefore raises no new
concerns that might affect the security of Internet users.  However, ensuring
that proper protocol maintenance can be conducted by qualified and motivated
experts could improve security.


# IANA Considerations

This document has no IANA actions.


--- back

# Acknowledgments
{:numbered="false"}

TODO acknowledge.
