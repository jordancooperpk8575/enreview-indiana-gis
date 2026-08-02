# EnReview Dashboard vUnversioned - Indiana Environmental Review Web App 2026

> **EnReview Dashboard is a browser-based Indiana environmental review tool for locating properties, viewing DNR and INDOT GIS information, and producing Section 106 review materials.**

[![Platform](https://img.shields.io/badge/Platform-Web%20browser-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-Unversioned-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/jordancooperpk8575/enreview-indiana-gis?style=flat-square)](https://github.com/jordancooperpk8575/enreview-indiana-gis)

---

<p align="center">
  <a href="https://jordancooperpk8575.github.io/enreview-indiana-gis/">
    <img src="https://img.shields.io/badge/Download-EnReview%20Dashboard%20Latest-brightgreen?style=for-the-badge" alt="Download EnReview Dashboard">
  </a>
</p>

> **[Download EnReview Dashboard](https://jordancooperpk8575.github.io/enreview-indiana-gis/)**

---

[Download Latest Build](https://jordancooperpk8575.github.io/enreview-indiana-gis/)

---

## Overview

EnReview Dashboard brings several Indiana environmental review tasks into one web-based workspace. Users can search by address, coordinates, or property ID; locate properties on a map; define review areas; and inspect GIS information related to historic resources and Section 106 work. Available data views may include historic properties, bridges, cemeteries, districts, managed land, and other mapped resources.

A review area can be created with a buffer, dropped pins, a drawn polygon, or the current map extent. The application then retrieves information from live DNR and INDOT GIS services. Returned properties can be filtered, sorted, marked as reviewed, opened through official records or Street View, and exported as a property list for a letter. EnReview Dashboard is distributed as a single HTML file and does not need a separate installation.

---

## Key Capabilities

- Find Indiana locations using street addresses, coordinates, or property IDs.
- Establish review boundaries with buffers, pins, polygons, or the current map view.
- Retrieve current information from Indiana DNR and INDOT GIS services.
- Display historic properties, bridges, cemeteries, districts, managed land, and related resources.
- Narrow and arrange properties by filtering and sorting the review results.
- Track progress by marking individual records as reviewed.
- Identify and manage records that may be duplicates.
- Follow links to official records and Street View from property results.
- Export reviewed properties as a list prepared for use in a letter.
- Use the application as a single browser file with no installation step.

---

## Getting Started

The application is designed to open directly in a modern web browser.

1. Get the current build from [Download Latest Build](https://jordancooperpk8575.github.io/enreview-indiana-gis/).
2. Open the downloaded HTML file in a browser.
3. Search using an address, coordinate pair, or property identifier.
4. Select a review-area method and load the available GIS records.

To work from a local checkout, clone the repository and enter its directory:

```bash
git clone https://github.com/jordancooperpk8575/enreview-indiana-gis.git
cd REPO
```

Open the primary HTML file in a web browser to launch the application.

---

## Review Workflow

The following sequence describes a standard use of EnReview Dashboard:

1. Locate the Indiana project using an address, coordinates, or property ID.
2. Select how the review area should be defined:
   - A buffer around the selected location
   - One or more dropped pins
   - A polygon drawn on the map
   - The current map extent
3. Request data from the available DNR and INDOT GIS services.
4. Examine the properties and records mapped within the chosen area.
5. Filter or sort the returned data according to the property types of interest.
6. Mark completed records as reviewed and flag potential duplicates for later attention.
7. Open official source records or Street View for additional investigation.
8. Export the reviewed property list for inclusion in review correspondence.

---

## Configuration and Data Use

EnReview Dashboard is controlled from its browser interface and does not use a separate setup wizard. Search fields, map controls, review filters, and result actions are used to define the work area and organize the properties returned by the application.

Since the software is delivered as one HTML file, retain that file with the project materials used for the review. During a review, the application requests GIS information through its connected services.

---

## Requirements

- A modern web browser.
- Internet access to query live DNR and INDOT GIS services.
- Indiana address, coordinate, or property details to use as search input.
- Enough local storage for the single HTML application file and exported results.
- No separate runtime or package installation.

---

## Frequently Asked Questions

### What type of work is EnReview Dashboard intended to support?

The tool is intended for Indiana environmental review and Section 106 workflows involving historic properties and other mapped resources.

### Is installation required?

No. The application runs in the browser from a single HTML file.

### Which search inputs are supported?

You can search with an Indiana street address, coordinates, or a property ID.

### What options are available for defining the review area?

The review boundary may be created with a buffer, dropped pin, drawn polygon, or the map's current extent.

### What services supply the mapped data?

EnReview Dashboard queries live DNR and INDOT GIS services and displays applicable mapped property categories in the dashboard.

### Is there an export function?

Yes. The reviewed property list can be exported in a format intended for use in a letter.

### What can I check when the search returns no results?

Verify the address or property identifier, review the selected area definition, and make sure the browser is online so it can reach the GIS services.

### How are new versions distributed?

New versions are made available through the project's latest published build. Use the project download link to obtain the current build when an update is published.

---

## Roadmap

- Further improve Indiana environmental review workflows.
- Refine the way mapped property results are organized.
- Add to the practical review and export functionality.
- Preserve compatibility with the applicable DNR and INDOT GIS services.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
