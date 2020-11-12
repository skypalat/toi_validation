# toi_validation
Here are posterior files for the RadVel fits and isochrone analysis of GJ1008b, Wolf 437b, and HD183579b as well as a list of the chi^2 values used in computing the FAP for each planet.

TOI_radvel_posteriors.zip contains compressed .pickle files with posteriors for K, jitter, eccentricity (e), omega (w), dvdt, curvature, and gamma for each planet in dictionary format. 

TOI_isochrones.zip contains compressed .dat files with planetary and stellar isochrone values. The .dat files ending in 'plan.dat' include values for Rp/R*, rho* [kg/m3], b, P, tmid, q1, q2, e, and w for each planet. The .dat files titled 'post.dat' include values for Teff, logg, Fe/H, stellar mass, stellar radius, age, logL, distance [pc], and extinction coefficient for each host star. 

The .dat files in FAP_chi2_scores include all of the chi^2 values used in our FAP analysis for each planet, where the first chi^2 in each file is the true chi^2 and the rest of them are the fake chi^2 values to test against.
