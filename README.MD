# 3D-Printed Linear Rails

A small collection of experimental 3D-printable linear rail designs for maker projects, prototypes, and motion systems.

The goal of this repository is **not** to replace commercial steel linear rails in applications that require high precision, high loads, or long service life. Instead, these designs explore how far simple printed rails can be pushed when low cost, easy fabrication, and custom geometry are more important than maximum rigidity.

## MGN9 PETG + PTFE Rail

This repository now includes a printable rail designed as a lightweight replacement for an **MGN9-style linear rail**.

The rail itself is printed in **PETG** and uses **PTFE tubing** as the sliding contact surface. The design was created to fit as closely as possible into the space occupied by the original MGN9 rails, allowing it to be tested on an existing CoreXY printer with minimal modification.

Each printed rail weighs roughly **15 g**.

### Why?

This started as a simple experiment:

> What happens if the steel linear rails of a fast CoreXY 3D printer are replaced with rails printed in PETG?

Surprisingly, during testing the printer remained fully functional and produced very good results. In this particular machine, the printed rails also produced a noticeably smoother surface finish on the test parts.

One possible explanation is that the slight compliance of the PETG/PTFE system helps damp some of the vibrations transmitted through conventional ball-bearing linear guides. This is only an observation from this specific test setup and should not be interpreted as proof that printed rails are generally superior to steel linear rails.

## Intended Use

These designs may be useful for:

- Experimental motion systems
- Low-cost prototypes
- Lightweight mechanisms
- Maker projects
- Custom machines where standard rail dimensions are inconvenient
- Projects where the rail geometry needs to be modified or integrated into another printed part

They are **not intended as drop-in replacements for steel rails in every application**.

For high precision, high loads, high temperatures, safety-critical systems, or long-term industrial use, conventional linear guides remain the appropriate choice.

## Printing

Recommended starting point for the MGN9-style rail:

- **Material:** PETG
- **Sliding surface:** PTFE tube
- Print with enough perimeters to keep the rail body stiff
- Use good layer adhesion
- Avoid overtightening mounting screws

> **Important:** PETG can crack or deform around screw holes if fasteners are overtightened. Tighten only enough to secure the rail.

Exact print settings may need to be adjusted depending on your printer, filament, and intended application.

## Files

The repository contains several experimental/reference rail designs.  
Check the individual folders and filenames for the corresponding geometry and version.

Where possible, both printable files and editable/source files are included.

## Experimental Design

These parts are experimental.

Performance will depend heavily on:

- Print orientation
- Material and filament quality
- Layer adhesion
- PTFE tube dimensions
- Mounting accuracy
- Load
- Speed and acceleration
- Temperature
- Wear over time

Long-term durability has not been fully characterized.

## Video

The MGN9 PETG/PTFE rails were tested on a high-speed CoreXY 3D printer for a Printabot video.

Video link: **Coming soon**

## License

Please check the repository license before using, modifying, or redistributing the files.

## Disclaimer

Use these designs at your own risk.

They are intended for experimentation, prototyping, and maker projects. Always evaluate whether a printed motion component is appropriate for the loads, speeds, temperatures, and safety requirements of your particular application.
