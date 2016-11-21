# Eyezheimers

This is a fork off the original Eyezheimers idea written by a team of 3 at HackDuke, based off of research by [Mahmoudian et al.](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3129106/): me, [yanbofang](https://github.com/yanbofang), and [mtran97](https://github.com/mtran97).

The project was based on the above research which basically stated that when eyedrops containing 0.005% diluted tropicamide solution were applied to people without Alzheimers, the size of their pupil stayed approximately the same. However, when those with Alzheimers had the drops applied, after approximately 40 minutes, their pupils dialated from a normal 100% to about 120% as opposed to very slight dialation in those without the disease.

What my plan to do here is to use more robust processing methods with OpenCV to analyze parts of the face as both a way of learning and to improve on ideas that we came up with during HackDuke. Eventually, I hope that this can lead to live tracking of the face and real-time detection of the pupil as opposed to only periodic snapshots.

## Potential challenges to overcome:
* Better movement analysis for more accurate data
* Better handling of fairly low resolution images that come from typical webcams - Many times the pupil is difficult to locate since it blends in with the iris. We found this is fairly characteristic of low-res photos.
* Glare and Reflection - This has to do with the pupil analysis itself. We want make sure that areas of glare don't affect the calculated size of the pupil and ratio.

![alt text](http://i.imgur.com/bFdO22v.png "Eye") ![alt text](http://i.imgur.com/ohL2GQG.png "Analyzed Eye")
