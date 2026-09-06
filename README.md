# TheMesozoic FModel

FModel exports from **The Isle / Evrima**, used as reference data during development of TheMesozoic.

## Purpose

This repository contains exported game assets and data generated with FModel. It is intended as a reference source for:

- Unreal Engine asset structures
- Data tables and configuration
- Maps and world data
- Blueprint-related exported information
- AI/world-partition information
- Game metadata
- Other exported Evrima game internals

## Repository structure

    Exports/
      TheIsle/
        Content/
        AssetRegistry.json
        ...

The Exports/ directory mirrors the FModel export structure.

## Important

This repository contains **reference/export data**, not the project's source code.

The main project is maintained separately in:

- TheMesozoic
- TheMesozoic-UE4SS

The UE4SS repository contains the runtime modding environment, mods, UE4SS configuration, signatures/object dumps, and related development material.

## Large files

A small number of very large FModel JSON exports are stored using Git LFS.

The original FModel archive is intentionally not stored in this repository because the extracted export tree is the useful/searchable representation.

## Source

Exports were generated from FModel for the Evrima game data used during TheMesozoic development.
