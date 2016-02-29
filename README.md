#  Identify relevant galaxy properties

Summary -- ThecosmologicalsimulationsmustbeturnedintocatalogsadheringtotheCatSim schema with parameterized
galaxy properties. This will include a combination of prescriptions for predicting galaxy properties, fitting
(for example SEDs), and mapping from one observable parameterization to another in order to satisfy the schema
of the input catalogs. This should come with a document describing the operations as well as code written
against the LSST project APIs for doing the conversions.

## Key Tasks
* Key Task CS2.2.1 ( 03/17 ): Produce a document describing how mappings from simulated
parameters to observable galaxy parameters should be done.
* Key Task CS2.2.2 ( 06/17 ): Deliver a code library written against the LSST CatSim APIs to execute the
mappings.

### Suggested organization
Repositories are available per deliverable.  Each key task has a subdirectory.
We have a `source` directory in each key task area for any supporting
code that goes with an effort.  There will also be a `doc` directory to hold documents in markdown,
latex, or binary formats.  The idea is to version everything and give us a good way to diff things.

Each deliverable is slightly different, so these repositories should grow to support the different need.

Please feel free to use github issues on each repository to organize work.
