---
title: "How satellite Earth observation data becomes a governed asset"
description: "Earth observation satellites now produce imagery at near-numberplate resolution with near-real-time frequency. The commercial question is not how to get the data — it is how to govern it as an asset."
keywords: satellite data governance, earth observation data asset, EO data management, satellite imagery governance, remote sensing data
date: 2026-05-07
---

# How satellite Earth observation data becomes a governed asset

In 2025, approximately 4,500 satellites were launched — around 11 per day. Commercial Earth observation (EO) providers now offer imagery at resolutions approaching 25 centimetres, with coverage frequency moving from daily to near-real-time as constellation sizes grow.

The barrier to accessing satellite data has collapsed. The barrier to making satellite data valuable has not.

## What satellite EO data is

Earth observation from satellites produces several distinct data types, each with different applications and governance requirements:

**Optical imagery.** Photographs of the Earth's surface in visible and near-infrared wavelengths. Used for land cover mapping, vegetation analysis, infrastructure monitoring, and change detection. Resolution ranges from 10 metres (ESA Sentinel-2, free) to sub-metre (commercial providers).

**Synthetic Aperture Radar (SAR).** Radar-based imaging that penetrates cloud cover and works in darkness. Used for flood extent mapping, subsidence monitoring, ship detection, and deformation analysis. ICEYE and other commercial providers offer near-daily SAR coverage for defined areas.

**Multispectral and hyperspectral data.** Imagery across multiple wavelength bands beyond visible light. Used for vegetation health assessment (NDVI), water quality monitoring, mineral mapping, and crop yield estimation.

**Thermal and atmospheric data.** Land surface temperature, sea surface temperature, atmospheric gas concentrations. Used for urban heat island analysis, marine ecosystem monitoring, carbon flux measurement, and wildfire risk assessment.

**Derived intelligence products.** AI-applied analysis of raw imagery that produces higher-level outputs: change alerts, object classifications, anomaly detections. A company like Planet does not only sell satellite images — it sells change detection at scale.

## The free data opportunity

A significant and under-used resource: the European Space Agency's Copernicus programme provides free access to Sentinel-2 optical imagery (10-metre resolution, 5-day revisit at mid-latitudes), Sentinel-1 SAR data, and a range of derived products through the Copernicus Open Access Hub.

Landsat data from USGS provides a free archive going back to 1972 — the longest continuous Earth observation record available. For organisations wanting to document how a landscape, coastline, or habitat has changed over decades, the Landsat archive is the starting point.

For many environmental monitoring applications — vegetation change, coastal erosion, land use conversion, urban expansion — the free Sentinel and Landsat archives provide sufficient resolution and coverage. The commercial satellite providers add value for applications requiring sub-metre resolution, near-real-time frequency, or specialist sensor types.

## Why EO data is not automatically an asset

Access to satellite data is easy. Turning satellite data into a governed asset requires:

**Provenance documentation.** Which satellite acquired this imagery? On which date? With which sensor settings? Processed by which algorithm? Any derived product must maintain a chain of provenance back to the source acquisition — otherwise the data cannot be validated by a third party.

**Methodology documentation.** An NDVI map derived from Sentinel-2 imagery means different things depending on how cloud masking was applied, which bands were used, and what quality flags were set. Without documented methodology, two analysts looking at the same underlying imagery can produce different results — and neither can be validated.

**Quality assessment.** EO data has known quality characteristics: cloud cover, atmospheric correction accuracy, geometric registration quality. A data asset record for an EO-derived product should document the quality of the underlying data and the confidence bounds on derived outputs.

**Rights documentation.** The terms under which data can be used vary by provider. Sentinel and Landsat data is open under permissive licences. Commercial EO data carries licensing terms that restrict onward distribution and sublicensing. A governed EO data asset includes documentation of the rights applicable to it — what the holder can do with it, and under what terms.

**Update and maintenance records.** An EO-derived dataset is not static. Coastlines change, vegetation changes, urban areas expand. A governed EO data asset includes a maintenance record: when was it last updated, what is its currency, and what is the plan for ongoing refresh.

## The value stack

EO data follows a well-established value chain:

1. **Raw imagery** — lowest value, available from multiple providers including free sources
2. **Processed imagery** — atmospherically corrected, geometrically registered, cloud-masked — modest value added
3. **Derived data products** — NDVI, land cover classifications, change detection maps — significant value added
4. **AI-applied intelligence** — alerts, anomaly detection, predictions — highest value
5. **Governed data assets** — any of the above levels, with documented provenance, methodology, quality, and rights — commercially licensable

The governance layer is what separates a data product from a data asset. It is the layer that allows the data to be licensed, to underpin a nature finance claim, to support a regulatory submission, or to attract investment.

## Applications for environmental data governance

For organisations managing environmental data — whether as a Biosphere Reserve, a conservation organisation, a government agency, or a corporate reporting against TNFD — governed EO data assets provide:

- A time-series record of environmental conditions that is verifiable and traceable
- A nature recovery evidence base that can support funding applications and public reporting
- A blue carbon evidence layer that can underpin carbon credit applications
- An ESG data source that can support sustainability reporting with third-party-verifiable data
- A spatial intelligence layer for the kind of digital twin infrastructure described in the UNESCO Biosphere Blueprint 2036

[Learn about the Biosphere as data infrastructure →](biosphere-as-data-infrastructure.md)
