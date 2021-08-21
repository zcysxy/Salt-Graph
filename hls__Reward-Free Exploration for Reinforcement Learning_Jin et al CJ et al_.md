file:: [Reward-Free Exploration for Reinforcement Learning_Jin et al CJ et al_.pdf](file://D:/OneDrive1/3-KNWL/33-Ref/CS/RL/Reward-Free Exploration for Reinforcement Learning_Jin et al CJ et al_.pdf)
file-path:: file://D:/OneDrive1/3-KNWL/33-Ref/CS/RL/Reward-Free Exploration for Reinforcement Learning_Jin et al CJ et al_.pdf

- Exploration is widely regarded as one of the most challenging aspects of reinforcement learning (RL),with many naive approaches succumbing to exponential sample complexity. To isolate the challengesof exploration, we propose a new “reward-free RL” framework. In the exploration phase, the agent firstcollects trajectories from an MDPMwithouta pre-specified reward function. After exploration, it istasked with computing near-optimal policies under forMfor a collection of given reward functions.This framework is particularly suitable when there are manyreward functions of interest, or when thereward function is shaped by an external agent to elicit desired behavior
  ls-type:: annotation
  hl-page:: 1
  id:: 6120a96b-8f17-4533-aa8c-800786326cd8
- We give an efficient algorithm that conducts ̃O(S2Apoly(H)/ǫ2)episodes of exploration and re-turnsǫ-suboptimal policies for anarbitrarynumber of reward functions. We achieve this by findingexploratory policies that visit each “significant” state with probability proportional to its maximum vis-itation probability underanypossible policy. Moreover, our planning procedure can be instantiated byany black-box approximate planner, such as value iterationor natural policy gradient. We also give anearly-matchingΩ(S2AH2/ǫ2)lower bound, demonstrating the near-optimality of our algorithm in thissetting
  ls-type:: annotation
  hl-page:: 1
  id:: 6120a9b0-cb7a-45b8-b13f-dfd73efcad37
- [:span]
  ls-type:: annotation
  hl-page:: 1
  id:: 6120a9ec-481c-4026-b6da-797b215dee13
  hl-type:: area
  hl-stamp:: 1629530602145