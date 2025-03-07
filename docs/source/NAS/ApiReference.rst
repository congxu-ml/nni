Retiarii API Reference
======================

.. contents::

Inline Mutation APIs
--------------------

..  autoclass:: nni.retiarii.nn.pytorch.LayerChoice
    :members:

..  autoclass:: nni.retiarii.nn.pytorch.InputChoice
    :members:

..  autoclass:: nni.retiarii.nn.pytorch.ValueChoice
    :members:

..  autoclass:: nni.retiarii.nn.pytorch.ChosenInputs
    :members:

..  autoclass:: nni.retiarii.nn.pytorch.Repeat
    :members:

..  autoclass:: nni.retiarii.nn.pytorch.Cell
    :members:

Graph Mutation APIs
-------------------

..  autoclass:: nni.retiarii.Mutator
    :members:

..  autoclass:: nni.retiarii.Model
    :members:

..  autoclass:: nni.retiarii.Graph
    :members:

..  autoclass:: nni.retiarii.Node
    :members:

..  autoclass:: nni.retiarii.Edge
    :members:

..  autoclass:: nni.retiarii.Operation
    :members:

Evaluators
----------

..  autoclass:: nni.retiarii.evaluator.FunctionalEvaluator
    :members:

..  autoclass:: nni.retiarii.evaluator.pytorch.lightning.LightningModule
    :members:

..  autoclass:: nni.retiarii.evaluator.pytorch.lightning.Classification
    :members:

..  autoclass:: nni.retiarii.evaluator.pytorch.lightning.Regression
    :members:

Oneshot Trainers
----------------

..  autoclass:: nni.retiarii.oneshot.pytorch.DartsTrainer
    :members:

..  autoclass:: nni.retiarii.oneshot.pytorch.EnasTrainer
    :members:

..  autoclass:: nni.retiarii.oneshot.pytorch.ProxylessTrainer
    :members:

..  autoclass:: nni.retiarii.oneshot.pytorch.SinglePathTrainer
    :members:

Exploration Strategies
----------------------

..  autoclass:: nni.retiarii.strategy.Random
    :members:

..  autoclass:: nni.retiarii.strategy.GridSearch
    :members:

..  autoclass:: nni.retiarii.strategy.RegularizedEvolution
    :members:

..  autoclass:: nni.retiarii.strategy.TPEStrategy
    :members:

..  autoclass:: nni.retiarii.strategy.PolicyBasedRL
    :members:

Retiarii Experiments
--------------------

..  autoclass:: nni.retiarii.experiment.pytorch.RetiariiExperiment
    :members:

..  autoclass:: nni.retiarii.experiment.pytorch.RetiariiExeConfig
    :members:

CGO Execution
-------------

..  autofunction:: nni.retiarii.evaluator.pytorch.cgo.evaluator.MultiModelSupervisedLearningModule

..  autofunction:: nni.retiarii.evaluator.pytorch.cgo.evaluator.Classification

..  autofunction:: nni.retiarii.evaluator.pytorch.cgo.evaluator.Regression

Utilities
---------

..  autofunction:: nni.retiarii.basic_unit

..  autofunction:: nni.retiarii.model_wrapper

..  autofunction:: nni.retiarii.fixed_arch


