# Player-Impact-Model
This project aims to develop a comprehensive Player Impact Model designed to quantify a basketball player’s total contribution to team success by integrating a full season of both individual performance metrics and on/off court impact data. The objective is to move beyond traditional box score statistics and create a more accurate, data-driven measure of how players influence game outcomes.

The model is built on two primary components: box score impact and on/off impact. Box score impact captures a player’s offensive and defensive contributions using normalized statistics such as scoring efficiency, playmaking, rebounding, and defensive events. These metrics provide a stable foundation for evaluating individual production.

To address the limitations of box score data, the model incorporates on/off court performance, which measures the difference in team net rating when a player is on the court versus when they are off. This component reflects a player’s real-world influence on team performance, including factors not fully captured in traditional statistics, such as spacing, defensive positioning, and off-ball movement. To improve reliability, on/off values are adjusted for sample size using minutes played and normalized to prevent disproportionate influence.

The final Player Impact Score is calculated as a weighted combination of these components, with weights determined using regression techniques. This approach places greater emphasis on box score data for stability while incorporating on/off impact to account for contextual and team-based effects.

The goal of this model is to evaluate player value more holistically by combining traditional statistical production with measurable impact on team performance. By doing so, the model provides a more complete understanding of how players contribute to winning and offers a data-driven framework for comparing player value across the league.
