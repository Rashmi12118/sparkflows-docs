
MulticlassClassificationEvaluator
========== 

Evaluator for multiclass classification, which expects two input columns: score and label.

Type
---------- 

ml-evaluator

Class
---------- 

fire.nodes.ml.NodeMulticlassClassificationEvaluator

Fields
---------- 

+---------------+-------------------+-------------------------------------+
| Name          | Title             | Description                         |
+===============+===================+=====================================+
| labelCol      | Label Column      | The label column for model fitting. |
+---------------+-------------------+-------------------------------------+
| predictionCol | Prediction Column | The prediction column.              |
+---------------+-------------------+-------------------------------------+
| metricName    | Metric Name       | The metric used in evaluation.      |
+---------------+-------------------+-------------------------------------+