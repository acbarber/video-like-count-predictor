# video-like-count-predictor
For YouTube content creators, the number of
views their videos receive not only dictates the
videos popularity, but also its ad revenue. For
those with monetary investment in YouTube,
the number of views a video receives directly
correlates with its contribution to their livelihood,
growth of their business or increase in
their social media presence. By looking at the
description of the video, it is possible to get a
brief overview of the content and therefore estimate
correlations between video content and
number of views. This view-estimation algorithm
can help guide creators on ideal content
for maximum viewership. We used both the
video description and the description + video
title as input into a simple Long-Short Term
Memory (LSTM) model in order to predict
YouTube view counts. We found that when using
both the video description and title in our
model, we were able to predict view counts
just as well as taking the median view counts
per YouTube channel. This finding represents
a jumping off point for future research in this
area, as well as a powerful tool for new content
creators looking
