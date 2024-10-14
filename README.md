# Techpoint_DataScience_WorkPrompt_2024
## Summary of Dataset Statistics

## Fan Challenges Completed
- **Mean**: 5.79 challenges
- 50% of participants completed 6 challenges, with a minimum of 1 and a maximum of 10.

## Predictive Accuracy
- **Mean accuracy**: 74.99%, with a wide range (50% to 98%).
- Half of the predictions are above 77%, suggesting a relatively strong model performance overall.

## Virtual Merchandise Purchases
- **Mean**: 2.67 purchases, ranging from 0 to 6.
- The 50% mark is at 2 purchases, indicating a moderate level of engagement with virtual merchandise.

## Sponsorship Interactions (Ad Clicks)
- **Mean**: 8.68 clicks, ranging from 0 to 19.
- The median user clicked 8 ads, showing decent interaction with sponsorships, though a significant variance is observed.

## Time on Live 360 (mins)
- **Mean**: 129.35 minutes, with users spending between 60 and 199 minutes.
- Most users (50%) spent around 124.5 minutes.

## Real-Time Chat Activity (Messages Sent)
- **Mean**: 25.05 messages sent, with a standard deviation of 14.16.
- Users sent between 0 and 49 messages, with the median at 25.5.

## Classification Model Results

### Logistic Regression
- **Accuracy**: 83%
- **Precision/Recall**: For predicting True (positive class), precision is 0.83, and recall is 1.00, indicating that the model is quite good at identifying true positives. However, for False predictions, precision and recall are 0.00, meaning the model struggles to identify negative cases.

### Decision Tree
- **Accuracy**: 70%
- **Precision/Recall**: For True, precision is 0.83, and recall is 0.80, slightly lower than logistic regression but still decent. The False precision is very low at 0.17, and the recall is 0.20, showing poor performance in predicting the False class.

### Random Forest
- **Accuracy**: 77%
- **Precision/Recall**: Precision for True is 0.82, and recall is 0.92, but for False, both precision and recall are 0.00. The weighted average accuracy of 77% indicates moderate success in handling the positive class but weak performance for negative predictions.

## Observations
- Across all models, identifying the False class remains a challenge, with precision and recall consistently near zero.
- The logistic regression model achieves the highest accuracy at 83%, followed by the random forest at 77%.
- Based on the metrics, models tend to perform well at identifying positive cases (i.e., predicting that users will engage or convert) but are weak at catching non-engaged users.
