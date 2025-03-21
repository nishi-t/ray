Examples using Ray Tune with ML Frameworks
------------------------------------------

.. raw:: html

    <a id="try-anyscale-quickstart-ray-tune-ml-frameworks" target="_blank" href="https://www.anyscale.com/ray-on-anyscale?utm_source=ray_docs&utm_medium=docs&utm_campaign=ray-tune-ml-frameworks">
      <img src="../../_static/img/run-on-anyscale.svg" alt="Run on Anyscale" />
      <br/><br/>
    </a>

.. toctree::
    :hidden:

    PyTorch Example <tune-pytorch-cifar>
    PyTorch Lightning Example <tune-pytorch-lightning>
    XGBoost Example <tune-xgboost>
    LightGBM Example <lightgbm_example>
    Hugging Face Transformers Example <pbt_transformers>
    Ray RLlib Example <pbt_ppo_example>
    Keras Example <tune_mnist_keras>
    Horovod Example <horovod_simple>


Ray Tune integrates with many popular machine learning frameworks.
Here you find a few practical examples showing you how to tune your models.
At the end of these guides you will often find links to even more examples.

.. grid:: 1 2 3 4
    :gutter: 1
    :class-container: container pb-3

    .. grid-item-card::
        :img-top: /images/keras.png
        :class-img-top: pt-2 w-75 d-block mx-auto fixed-height-img

        .. button-ref:: tune-mnist-keras

            How To Use Tune With Keras & TF Models

    .. grid-item-card::
        :img-top: /images/pytorch_logo.png
        :class-img-top: pt-2 w-75 d-block mx-auto fixed-height-img

        .. button-ref:: tune-pytorch-cifar-ref

            How To Use Tune With PyTorch Models

    .. grid-item-card::
        :img-top: /images/pytorch_lightning_small.png
        :class-img-top: pt-2 w-75 d-block mx-auto fixed-height-img

        .. button-ref:: tune-pytorch-lightning-ref

            How To Tune PyTorch Lightning Models

    .. grid-item-card::
        :img-top: /rllib/images/rllib-logo.png
        :class-img-top: pt-2 w-75 d-block mx-auto fixed-height-img

        .. button-ref:: tune-rllib-example

            Tuning RL Experiments With Ray Tune & Ray Serve

    .. grid-item-card::
        :img-top: /images/xgboost_logo.png
        :class-img-top: pt-2 w-75 d-block mx-auto fixed-height-img

        .. button-ref:: tune-xgboost-ref

            A Guide To Tuning XGBoost Parameters With Tune

    .. grid-item-card::
        :img-top: /images/lightgbm_logo.png
        :class-img-top: pt-2 w-75 d-block mx-auto fixed-height-img

        .. button-ref:: tune-lightgbm-example

            A Guide To Tuning LightGBM Parameters With Tune

    .. grid-item-card::
        :img-top: /images/horovod.png
        :class-img-top: pt-2 w-75 d-block mx-auto fixed-height-img

        .. button-ref:: tune-horovod-example

            A Guide To Tuning Horovod Parameters With Tune

    .. grid-item-card::
        :img-top: /images/hugging.png
        :class-img-top: pt-2 w-75 d-block mx-auto fixed-height-img

        .. button-ref:: tune-huggingface-example

            A Guide To Tuning Huggingface Transformers With Tune

    .. grid-item-card::
        :img-top: /images/tune.png
        :class-img-top: pt-2 w-75 d-block mx-auto fixed-height-img

        .. button-ref:: tune_train_tf_example

            End-to-end Example for Tuning a TensorFlow Model

    .. grid-item-card::
        :img-top: /images/tune.png
        :class-img-top: pt-2 w-75 d-block mx-auto fixed-height-img

        .. button-ref:: tune_train_torch_example

            End-to-end Example for Tuning a PyTorch Model with PBT
