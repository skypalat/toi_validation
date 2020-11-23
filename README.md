# toi_validation
Here are posterior files for the RadVel fits and isochrone analysis of HD183579b as well as a list of the chi^2 values used in computing the FAP for this planet.

HD183579_radvel_posteriors.csv contains the entire posterior file for HD183579b including K, jitter, eccentricity (e), omega (w), dvdt, curvature, and gamma, etc. 

TOI_isochrones.zip contains compressed .dat files with planetary and stellar isochrone values. The .dat files ending in 'plan.dat' include values for Rp/R*, rho* [kg/m3], b, P, tmid, q1, q2, e, and w for each planet. The .dat files titled 'post.dat' include values for Teff, logg, Fe/H, stellar mass, stellar radius, age, logL, distance [pc], and extinction coefficient for the host star. 

The .dat file in FAP_chi2_scores include all of the chi^2 values used in our FAP analysis for this planet, where the first chi^2 in the file is the true chi^2 and the rest of them are the fake chi^2 values to test against.
