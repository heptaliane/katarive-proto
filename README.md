# katarive-proto

This repository defines Protocol Buffer messages and services for the katarive project, including:

   - api/v1/api.proto: Defines the main KatariveService for creating narrations from URLs and checking the status of narration jobs.
   - plugin/v1/narrator.proto: Defines the NarratorService interface for narration plugins, including methods to get metadata, initiate narration, and check job status.
   - plugin/v1/source.proto: Defines the SourceService interface for source plugins, with methods to extract content from URLs and list supported URL patterns.
