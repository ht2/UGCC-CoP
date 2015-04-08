# Vocabulary
This document defines the identifiers and extensions used for UGCC Sharing. Examples can be found in the [readme](readme.md) of this directory.

## Identifiers
*Use the IRIs hyperlinked to the text in the identifiers column, rather than the words themselves. At least one of the "Alternative Required" identifiers must be used.*

xAPI Property | Identifier | Description | Required
--- | --- | --- | ---
verb.id | [Shared](http://activitystrea.ms/schema/1.0/share) | States the `actor` shared the `object`. | Required
object.definition.type | [Page](http://activitystrea.ms/schema/1.0/page) | States that the `object` is a page. | Alternative Required
object.definition.type | [File](http://activitystrea.ms/schema/1.0/file) | States that the `object` is a file. | Alternative Required
context.contextActivities.category.N.id | [UGCC Recipe](https://github.com/ht2/UGCC/releases/tag/v0.0.1) | States the statement uses the UGCC recipe. | Required
context.contextActivities.grouping.N.definition.type | [Course](http://adlnet.gov/expapi/activities/course) | States that the `object` is part of a course. | Required

## Extensions
*Use the IRIs hyperlinked to the text in the extension column, rather than the words themselves.*

xAPI Property | Extension | Description | Required
--- | --- | --- | ---
- | - | - | -
