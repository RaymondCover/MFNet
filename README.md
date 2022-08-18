# MFNet
RGB-T Tracking by Modality Difference Reduction and Feature Re-selection

[[Paper Link]](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4137009/)

# Introduction
RGB-T tracking has attracted increasing attention, since visible and thermal data have strong complementary advantages to improve the robustness of trackers. Most existing models focus on investigating efficient ways of fusing the complementary information from RGB and thermal images for better tracking performance. However, the modality differences caused by different imaging mechanisms may degrade the discriminability of the fused features. Meanwhile, compared with the unimodal features, the fused features may not always improve the tracking performance, especially when one of the input images contain much noisy information. In view of this, we propose a novel RGB-T tracking model by simultaneously reducing modality difference and re-selecting discriminative features from the fused features as well as from the unimodal features. To this end, a Modality Difference Compensation module (MDC) and a Feature Re-selection module (FRS) are presented. The former one reduces the modality differences between RGB and thermal features and obtains the fused features. The latter one adaptively selects such discriminative features from the unimodal features and the fused features for the subsequent classification and regression. Exhausted experiments are conducted on three RGB-T tracking benchmark datasets, which verify that our proposed tracker performs favorably against some state-of-the-art tracking algorithms.

# Tracking results
