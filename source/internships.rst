Internships 
**************
I have conducted multiple internships during both my undergraduate and post-graduate studies. The majority of these have been in galactic astrophysics, however, I do also have experience in industry as well as some other minor fields of physics.
This page will briefly detail the projects that I conducted, and how they fit in with my overall experience. It will also highlight any publications as a result of the work.

Harnessing the Hubble Archives: Searching for Interacting Galaxies
======================================================================
| Location: `European Space Astronomy Centre (ESAC) <https://www.esa.int/About_Us/ESAC>`_
| Supervisor: `Bruno Merin <http://brunomerin.com/>`_
| Dates: 4\ :sup:`th` May 2022 - 8\ :sup:`th` Jul 2022

Interacting Galaxies are some of the most observationally striking systems we can observe (at least, in my opinion). Two examples are shown on the homepage of this site, showing the minor interaction of NGC 5907 and the major interaction of Arp
240. The resultant distortion of each galaxy and the features that form are dependent upon a host of underlying parameters. For example, a tidal tail may only form if the two galaxies collide at a certain angle, or the secondary galaxy may only
be destroyed if the primary has a specific mass. We therefore want to be able to explore the underlying parameter spaces of these systems and link different paramters to different features that form or underlying processes that occur. To do this,
we need a statistically robust sample of interacting systems. The existence of such a sample, I cannot find.

Existing interacting galaxy samples are often made by hand. Such as the very famous original interacting galaxy catalogue from `Halton Arp <https://en.wikipedia.org/wiki/Halton_Arp>`_. He compiled the first large catalogue of 338 interacting
systems in 1966 - hardly a sample we could call statistically significant. Future works added to this, with the `Vorontsov-Velyaminov <https://ned.ipac.caltech.edu/level5/VV_Cat/frames.html>`_ catalogue finished in 1972. Then, machine learning
techniques came on the scene and began to scower astronomical datasets for interacting galaxies. However, they came across a unique problem. They struggled to tell the difference between close pairs of galaxies (i.e. those that were close 
together by project effects) and actually interacting galaxies. Therefore, any interacting galaxies found by machine learning algorithms would still have to go through a step of manual review. This did enlarge our catalogues, however, with
the `Galaxy Zoo <https://www.zooniverse.org/projects/zookeeper/galaxy-zoo/>`_ collaboration finding 3,003 interacting or merging systems and the `North Ecliptic Pole Merging Galaxy Catalogue <https://www.aanda.org/articles/aa/full_html/2022/05/aa41013-21/aa41013-21.html>`_ 
finding 2,109. A significant improvement, but still short of samples we could call statistically robust and representative.

In this project, my aim was to create an interacting galaxy catalogue significantly larger than those found previously. We would use machine learning algorithms to do this, but with two unique approaches which would increase our chances of success.
The first was to use a new advanced convolutional neural network (CNN) called `Zoobot <https://zoobot.readthedocs.io/en/latest/>`_ created by `Mike Walmsley <https://research.manchester.ac.uk/en/persons/michael.walmsley>`_. This CNN has the advantage over previous models 
as it utilises `representation learning <https://en.wikipedia.org/wiki/Feature_learning>`_ to increase the accuracy of its outputs. We also used a new platform: `ESA Datalabs <https://datalabs.esa.int/>`_. This platform allows us to directly mount space telescope data 
repositories (in this case, the `Hubble Legacy Archive <https://hla.stsci.edu/>`_) and use it as if it were full of local files. This removed the computationally costly step of having to get all 9,507 observation files that we wanted to investigate.

Using these two tools to our advantage, I scanned the entire Hubble Archives looking for interacting galaxies. In the end, we identified 21,926 confidently classified interacting galaxies. These results are written up and have been submitted to the
`Astrophysical Journal <https://iopscience.iop.org/journal/0004-637X>`_. A copy of the submitted paper can be found on GoogleDrive at this `link <https://drive.google.com/drive/folders/1mZaPOUmwpR_NbUydMHhimp55wSU3fgNg?usp=sharing>`_.

Industrial Placement
========================
| Location: `1715Labs <https://medium.com/1715labs>`_
| Supervisor: `Tim Lingard <https://uk.linkedin.com/in/tklingard>`_
| Dates: 1\ :sup:`st` Oct 2021 - 4\ :sup:`th` Jan 2022

1715Labs was a commercial offshoot of the `Zooniverse <https://www.zooniverse.org/>`_ platform. This platform focused on using citizen scientists (or volunteers) to address different research questions. In a commercial context, we used payed workers (akin to volunteers) to
label data and answer research questions for different clients. Most often, this was providing them accurate labels for large, complex dataserts which would be impossible to go through themselves. As an example, one project I worked on was annotating satellite images 
of farmland fields. The client needed to measure the areas of each field owned by different farmers for government data purposes. We therefore build a new image annotation tool, a full workflow and instruction manual so many workers would be able to annotate all 10,000 
images. We also created tests, which would allow us to weight each worker by their skill throughout the task. With the framework being set up, we could then send it out to the workers where they would annotate the full 10,000 images over night. A task which would have 
taken our client, or ourselves significantly longer.

This was just one example of the many projects I worked on during my three months at 1715Labs. I also worked on categorising satellite images of damaged houses following a hurricane, classifying different fast food/alcohol adverts which were being shown on social media
to users under 18 - an illegal practice under UK Law - and on counting graves in satellite images of cemetaries in the Yemen to help inform the UK governemnt of aid requirements there. 

While all very important projects, the main skills I gained from this internship was the ability to work with geospatial data. I gained extensive understanding and use of `GeoPandas <https://geopandas.org/en/stable/docs.html>`_, 
`Shapely <https://shapely.readthedocs.io/en/stable/>`_, `Fiona <https://fiona.readthedocs.io/en/latest/>`_ and `Pandas <https://pandas.pydata.org/docs/>`_ itself. Each of these I now use extensively in my PhD. Shapely in particular has been of use, as I am developing 
algorithms to recognise merger remnants using only their shape and none of their flux information. 


Enhancing Single Photon Avalanche Diodes in Pill Cameras with Super Resolution 
================================================================================
| Location: `University of Glasgow Imaging Concepts Group <https://www.gla.ac.uk/schools/physics/research/groups/imagingconcepts/>`_
| Supervisor: `Pavan Chandra Konda <https://scholar.google.co.uk/citations?user=WxeFhgcAAAAJ&hl=en>`_
| Dates: 18\ :sup:`th` Jun 2018 - 24\ :sup:`th` Aug 2018

`Endoscopy's <https://www.nhs.uk/conditions/endoscopy/#:~:text=An%20endoscopy%20is%20a%20test,endoscopy%20unit%20in%20a%20hospital.>`_ are an extremely necessary, but invasive procedure. A patient undergiong one must have a camera tube inserted down their throat to the 
area which must be examined. The camera tube is made of thick black rubber, with an optical fibre down it and a camera with a light at the end. The light is of the utmost importance, as there is very little light in the body; meaning the camera cannot detect anything 
unless another source of lumination is provided. 

To avoid such an invasive and uncomfortable procedure, `pill cameras <https://en.wikipedia.org/wiki/Capsule_endoscopy>`_ have been investigated as an alternative. These capsules are small enough for a patient to swallow, while containing all the necessary components to
image the gastric system. However, their main downside is the requirement for a light source to illuminate the gut. This is, by far, the largest power drain on the capsule and often means there is not enough battery power for the light source to illuminate the entire 
system. This project focused on a solution to this problem.

We proposed using a miniturized `Single Photon Avalanche Diode (SPAD) <https://en.wikipedia.org/wiki/Single-photon_avalanche_diode>`_ and natural `bioluminescence <https://en.wikipedia.org/wiki/Bioluminescence>`_ of the gut as an alternative to the CCD used in conventional 
pill cameras. The primary advantage of using a SPAD is that it is incredibly sensitive, being able to detect light down to the single photon level (hence the name). Therefore, instead of requiring a bright light source to illuminate the gut, we use a low-powered laser to 
activate the guts natural bioluminescence. This allows the batteries inside the pill camera to survive the entire gastric system, imaging the gut before being expelled.

The main disadvantage of using a SPAD, however, data reading section of each pixel takes up a large area of the pixel itself. The light-sensitive area only makes up about a third of each pixel, leading to atrocious resolution compared to a fully illuminated CCD. We therefore
used `super-resolution <https://en.wikipedia.org/wiki/Super-resolution_imaging>`_ techniques to try and improve this. The question we wanted to answer was, is the natural motion of the pill camera during `peristalsis <https://en.wikipedia.org/wiki/Peristalsis>`_ able to move 
the camera in a way which covers the readout areas of the pixel so that we can combine all the images later to make one comparable to the CCD? This could all be done in the post-processing of the images, meaning there would be no extra cost to the patient. We therefore 
created a microscope which moved and simulated the motion a pill camera would experience during natural peristalsis. We then took every image captured and drizzled similar images together to increase the SPADs resolution.

We found that while the illumination required was significantly lower (as expected), and that the pill capsule batteries would survive the entire expected time of going through the gut with our method. However, the superresolution images of the SPAD simply could not compare
to those of an illuminated CCD. For medical purposes, the images produced by the SPAD would be unusable.

Investigating the Local Group Satellite Plane in Modified Gravity
=========================================================================
| Location: `University of St Andrews Astronomy Group <https://astronomy.wp.st-andrews.ac.uk/>`_
| Supervisor: `Indranil Banik <https://risweb.st-andrews.ac.uk/portal/en/persons/indranil-banik(d66f0119-1735-4358-ab0f-4e5b5754d7b2).html>`_ \& `Hongsheng Zhao <https://risweb.st-andrews.ac.uk/portal/en/persons/hongsheng-zhao(7ee554cc-f5a0-4785-ac90-7576938eb6b4).html>`_
| Dates: 4\ :sup:`th` June 2017 - 18\ :sup:`th` Aug 2017

There are a whole host of galaxies orbiting the Milky Way and Andromeda galaxies. Curiously, these satellite galaxies orbit each of their host galaxies in very flat planes (flat compared to other galaxy satellite systems observed). This has long been very difficult to 
predict and model using the standard model of cosmology :math:`\Lambda` Cold Dark Matter (`LCDM <https://en.wikipedia.org/wiki/Lambda-CDM_model>`_). This theory states that matter forms in a hierarchical bottom-up way with smaller galaxies merging into larger galaxies
through cosmic time. However, assuming this formation method and then running `hydrodynamical cosmological simulations <https://en.wikipedia.org/wiki/Smoothed-particle_hydrodynamics>`_ of the universe we find that satellite systems as flat and co-rotating as ours are
extremely rare - to the point of should be impossible. Therefore, we look at alternative theories which may be able to explain our flat, co-rotating satellite planes. 

The theory we explored was that of Modified Newtonian Dynamics (`MOND <https://en.wikipedia.org/wiki/Modified_Newtonian_dynamics>`_). This is an alternative gravity theory which does not require the existence dark matter to explain the discrepancy between observed and 
expected `galaxy rotation curves <https://en.wikipedia.org/wiki/Galaxy_rotation_curve>`_. Rather than add invisible mass (dark matter) in order to solve the rotation curve problem, MOND stipulates that in the outer reaches of the galaxy the gravitational force begins to 
vary inversely linearly with radius rather than the square of the radius. This violation of Newton's laws occur (or, are hypothesised to occur) at extremely small accelerations, charactistic of galaxies but not typically encountered in in our local region. Therefore,
by defining these two different regimes of acceleration and where the law of gravity changes, we can build simulations of the satellite planes.

A crucial component of MOND is that in the past, the Andromeda and Milky Way galaxies had a close flyby and interaction. This then led to the formation of each systems satellite planes, as material was pulled out of each galaxy in this interaction. We built simulations to 
model this close flyby and the following cumulation of outer material into our satellite galaxies. We can then make a measure of the thickness of the satellite plane, the pole of angular momentum of the satellite plane, how the objects rotate about the Milky Way and
Andromeda and the thickness of disks of both host galaxies. From our simulations, we were able to match each of these parameters to their observed values. These results were subsequently published in the Monthly Notices of the Royal Astronomical Society 
`here <https://ui.adsabs.harvard.edu/abs/2018MNRAS.477.4768B/abstract>`_.

Modelling Bar Formation in the Core of the Milky Way
============================================================
| Location: `Nicolas Copernicus Astronomical Centre <https://www.camk.edu.pl/>`_
| Supervisor: `Ewa Lokas <http://users.camk.edu.pl/lokas/>`_
| Dates: 4\ :sup:`th` Jul 2016 - 12\ :sup:`th` Aug 2016

The existence of central bar in the Milky Way is now an accepted in astronomy. However, back during this project it was not such an obvious fact. A large scale, hydrodynamical simulation of the Milky Way in isolation had been run, where a bar formed through natural
processes. This was a very idealised scenario. As stipulated in LCDM, galaxies form hierarchically, so therefore assuming the Milky Way had been in isolation throughout history is unlikely. These simulations are still useful, however, to study bar evolution through
cosmic time. 

My task was to take the outputs of 50 snapshots during the idealised simulation, and to measure the bar parameters at each timestep, and plot its evolution. Following this, I attempted to model how this bar would look in the night sky from the Suns position within the 
Milky Way. We then aimed to qualitatively compare the resultant mass distribution from this position to that in the physical night sky. Upon doing this, we found significant mismatch between the simulated mass distribution in the sky and the observed one. As stated before,
this idealised scenario would have made it unlikely that any match could be found. 