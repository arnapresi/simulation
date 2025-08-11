
| Folder           | Code                                      | Explanation |
|------------------|-------------------------------------------|-------------|
| Checkers         | EddingtonRatio_checker.ipynb              | Given a haloID gives the eddington ratio for the central blackhole |
| Checkers         | fedd_disrtibution.ipynb                    | Various ways of plotting eddington ratio distribution given a redshift and simulation |
| Checkers         | halo_checker.ipynb                         | Given a haloID it gives halo and central subhalo details |
| Checkers         | HaloMassFunction.ipynb                     | Gives the halo mass functions for given simulation (TNG50, TNG100, TNG300 here) |
| Checkers         | max_eddhmbh.ipynb                          | Given a specific redshift and simulation gives the maximum halo mass, blackhole mass and maximum eddington ratio vales and their corresponding haloID |
| Checkers         | redshift_time_distance.ipynb               | Given a specific redshift calculates the lookback time and comoving distance |
| Checkers         | subhalo_checker                            | Given a subhaloID it gives subhalo and parent halo details |
| CAMELS           | 1P_1_0.ipynb                               | Given a folder of CAMELS Xray file generates maps of all the haloIDs in that folder (here 1P_1_0 folder) |
| CAMELS           | 1Pmap_generator.ipynb                      | Given a specific haloID (here haloID 0) plots maps for all parameter combinations in 1P set. |
| CAMELS           | CVmap_generator.ipynb                      | Given a specific haloID (here haloID 0) plots maps for all parameter combinations in CV set. |
| CAMELS           | EXmap_generator.ipynb                      | Given a specific haloID (here haloID 0) plots maps for all parameter combinations in EX set. |
| CAMELS           | LHmap_generator.ipynb                      | Given a specific haloID (here haloID 0) plots maps for all parameter combinations in LH set. |
| CAMELS           | maps_generator_CAMELS.ipynb                | Given a specific simulation and redshift and a set minimum and maximum energy range (in keV) this code generates thermodynamic gas profiles (density, temperature, pressure, entropy, metallicity), theoretical xray maps (emissivity, intensity) and observational maps (here LEM) and spectrum for ICM (halogas) of specific haloID. |
| CAMELS           | xray_surface.ipynb                         | Given CAMELS surface brightness files generates radial profiles for EX set halo 0 and stacked radial profiles for all 93 halos in EX set. |
| CAMELS           | checker_CAMELS.ipynb                       | Giving specific conditions regarding halo mass cut off, blackhole mass cut off and central / satellite information the code categorizes the halos and gives haloIDs in each category. |
| CAMELS           | thermo3d_average_CAMELS.ipynb              | Stacked 3d thermodynamic radial profiles by considering sphere around halo center. Average is simple mean. |
| CAMELS           | xray2d_CAMELS.ipynb                         | Stacked 2d xray radial profiles based on line of projection information. Average is simple mean. |
| Generating_Maps  | maps_generator_TNG.ipynb                    | Given a specific simulation and redshift and a set minimum and maximum energy range (in keV) this code generates thermodynamic gas profiles (density, hot gas density, temperature, pressure, entropy, metallicity), theoretical xray maps (emissivity, intensity) and observational maps (here LEM) and spectrum of ICM (halo gas) or IGM / ISM (subhalo gas) for specific haloID or subhaloID. |
| Stacked_Profiles | compare_avg.ipynb                           | Compares different ways of calculating average in each radial bins: mean, median, volume weighted mean (manual or using yt), mass weighted mean (manual or using yt), spline weighted mean. |
| Stacked_Profiles | top10.ipynb                                 | Plotting radial thermodynamic profiles of top 10 halomass halos using TNG100 redshift 1. |
| Stacked_Profiles | checker_TNG.ipynb                           | Giving specific conditions regarding halo mass cut off, blackhole mass cut off and central / satellite information based on eddington ratio and luminosity cut off this code categorizes TNG halos in: effectively accreting AGN, effectively accreting nonAGN, ineffectively accreting AGN and ineffectively accreting nonAGN (based on two sets of conditions, 1. fixed eddington ratio threshold 0.1, 2. bhmass based TNG specific eddington ratio threshold) |
| Stacked_Profiles | thermo2d_TNG.ipynb                          | Stacked 2d thermodynamic radial profiles based on line of projection information. Average is simple mean. |
| Stacked_Profiles | thermo3d_average_TNG.ipynb                  | Stacked 3d thermodynamic radial profiles by considering sphere around halo center. Average is simple mean. |
| Stacked_Profiles | thermo3d_masswt_TNG.ipynb                    | Stacked 3d thermodynamic radial profiles by considering sphere around halo center. Average is mass weighted using yt. |
| Stacked_Profiles | thermo3d_spline_TNG.ipynb                    | Stacked 3d thermodynamic radial profiles by considering sphere around halo center. Average is calculated using spline smoothing. |
| Stacked_Profiles | xray2d_TNG.ipynb                            | Stacked 2d xray radial profiles based on line of projection information. Average is simple mean. |
| Cross_Correlation | xray_joxsz.ipynb                            | Given specific instrument and energy range generates source and background event files. |
| Cross_Correlation | tng_to_joxsz_eventlist_allbands.ipynb                            | Given specific source event file this code generates formatted foreground files for joxsz. |
| Cross_Correlation | tng_to_joxsz_eventlist_allbands_background.ipynb                            | Given specific background event file this code generates formatted background files for joxsz. |
