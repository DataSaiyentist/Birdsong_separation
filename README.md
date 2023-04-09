# Sound Separation of Bird Calls Using MixIT

Birds are all around us, and just by listening, we can learn many things about our environment. Ecologists use birds to understand food systems and forest health. For example, if there are more woodpeckers in a forest, that means there’s a lot of dead wood. 

The massive amount of available field recordings of birds prensents an opportunity to use machine learning (ML) to automatically track bird populations and better understand ecosystems.

However, ML-based audio classification of bird species can be challenging for several reasons. Indeed, field recordings typically contain significant environmental noise and overlapping vocalizations that interfere with classification. Additionally, some of the most common species often appear unlabeled in the background of training recordings for less common species, leading models to discount the common species.

To address the general challenge of training ML models to separate audio recordings without access to examples of isolated sounds, Google researchers have developped a unsupervised method called misture invariant training (MixIT). to separate birdsong and improve species classification. Below is a demonstration of birdsong separation from High Sierras (the video show the mel-spectogram of the mixed audio and highlight the audio separated into different tracks) :

<video width="320" height="240" controls>
  <source src="save/birbsep_aiblog_caples.mp4" type="video/mp4">
</video>

## References

<a href="https://arxiv.org/pdf/2006.12701.pdf">[1] Scott Wisdom, Efthymios Tzinis, Hakan Erdogan, Ron J. Weiss, Kevin Wilson, John R. Hershey, "Unsupervised Sound Separation Using Mixture Invariant Training", Advances in Neural Information Processing Systems, 2020.</a>

<a href="https://arxiv.org/pdf/2110.03209.pdf">[2] Tom Denton, Scott Wisdom, John R. Hershey, "Improving Bird Classification with Unsupervised Sound Separation", Proc. IEEE International Conference on Audio, Speech, and Signal Processing (ICASSP), 2022.</a>

## License

Copyright © 2023 [Data Saiyentist](https://github.com/DataSaiyentist). <br />
This project is [MIT License](https://github.com/DataSaiyentist/Birdsong_separation/blob/main/LICENSE) licensed.