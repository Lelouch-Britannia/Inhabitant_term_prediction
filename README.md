# City Inhabitant Nomenclature Predictor

Often cities have specific terms used to describe their inhabitants. For instance:

- **London** --> *Londoner*
- **Paris** --> *Parisian*
- **Delhi** --> *Delhitie*
- **Mumbai** --> *Mumbaikar*
- **Kolkata** --> *Kolkatan*
- **Berlin** --> *Berliner*


## Goal:

Develop a predictor which, given the name of a city, will provide the likely term for its inhabitants.


## Data Collection and Processing

### Data Collection:
1. **Source**: Wikipedia's [List of Adjectivals and Demonyms for Continents & Islands](https://en.wikipedia.org/wiki/Demonym)
2. Scrapped data was converted into a CSV format, comprising columns `Location` and `Demonym`.

### Data Processing:
1. Data was cleaned by converting all terms to lowercase for uniformity.
2. Where multiple demonyms existed for a single location, a single, commonly used demonym was chosen.

### Processed Data Snapshot:

| Location        | Demonym          |
|-----------------|------------------|
| africa          | africans         |
| antarctica      | antarcticans     |
| asia            | asians           |
| australia       | australians      |
| europe          | europeans        |
| north america   | north americans  |
| south america   | south americans  |
| central america | central americans|

---

This table and section provides a quick overview of your data collection and processing methodology.