# Kaggle_Desafio_Titanic_-_EBAC

    **RANDOM FOREST**

    **Cenário completo**
    - DADOS COMPLETOS, DESBALANCEADOS E DESPADRONIZADOS = CV [pontuacoes_complet_dp], Acurácia [accuracy_complet_dp] e F1-Score [report_rf__complet_dict_dp = classification_report(y_train, y_rf_train_pred_complet_dp, output_dict=True); f1_rf_complet_dp = report_rf__complet_dict_dp['macro avg']['f1-score']];
    - DADOS COMPLETOS, DESBALANCEADOS E DESPADRONIZADOS COM APLICAÇÃO DE HIPERPARÂMETROS = CV [pontuacoes_complet_dp_best], Acurácia [accuracy_complet_dp_best], F1-Score [report_rf_complet_dict_dp_best = classification_report(y_train, y_rf_train_pred_complet_dp_best, output_dict=True); f1_rf_complet_dp_best = report_rf_complet_dict_dp_best['macro avg']['f1-score']];
    - DADOS COMPLETOS, BALANCEADOS E PADRONIZADOS COM APLICAÇÃO DE HIPERPARÂMETROS = CV [pontuacoes_complet_best], Acurácia [accuracy_complet_best] e F1-Score [report_rf_complet_dict_best = classification_report(y_train_balanced, y_rf_train_pred_complet_best, output_dict=True); f1_rf_complet_best = report_rf_complet_dict_best['macro avg']['f1-score']];

    **Cenário selecionado**
    - DADOS SELECIONADOS, DESBALANCEADOS E DESPADRONIZADOS = CV [pontuacoes_select_dp], Acurácia [accuracy_select_dp] e F1-Score [report_rf_select_dict_dp = classification_report(y_train, y_rf_train_pred_select_dp, output_dict=True); f1_rf_select_dp = report_rf_complet_dict_best['macro avg']['f1-score']];
    - DADOS SELECIONADOS, DESBALANCEADOS E DESPADRONIZADOS COM APLICAÇÃO DE HIPERPARÂMETROS = CV [pontuacoes_select_dp_best], Acurácia [accuracy_select_dp_best] e F1-Score [report_rf_select_dict_dp_best = classification_report(y_train, y_rf_train_pred_select_dp_best, output_dict=True); f1_rf_select_dp_best = report_rf_select_dict_dp_best['macro avg']['f1-score']];
    - DADOS SELECIONADOS, BALANCEADOS E PADRONIZADOS COM APLICAÇÃO DE HIPERPARÂMETROS = CV [pontuacoes_select_best], Acurácia [accuracy_select_best] e F1-Score [report_rf_select_dict_best = classification_report(y_train_balanced, y_rf_train_pred_select_best, output_dict=True); f1_rf_select_best = report_rf_select_dict_best['macro avg']['f1-score']].

    **SVM**
    **Cenário completo**
    **Dados desbalanceados e despadronizados**
    - Kernel = "rbf" = CV [svm_pontuacoes_complet_dp], Acurácia [svm_accuracy_complet_dp] e F1-Score [report_svm_complet_dp_dict = classification_report(y_train, y_svm_train_pred_complet_dp, output_dict=True); f1_svm_complet_dp = report_svm_complet_dp_dict['macro avg']['f1-score']];

    - Kernel = "linear" = CV [svm_l_pontuacoes_complet_dp], Acurácia [svm_l_accuracy_complet_dp] e F1-Score [report_svm_l_complet_dp_dict = classification_report(y_train, y_svm_l_train_pred_complet_dp, output_dict=True); f1_svm_l_complet_dp = report_svm_l_complet_dp_dict['macro avg']['f1-score']];

    - Kernel = "poly" = CV [svm_p_pontuacoes_complet_dp], Acurácia [svm_p_accuracy_complet_dp] e F1-Score [report_svm_p_complet_dp_dict = classification_report(y_train, y_svm_p_train_pred_complet_dp, output_dict=True); f1_svm_p_complet_dp = report_svm_p_complet_dp_dict['macro avg']['f1-score']];

    - Aplicação de hiperparâmetros no SVM com os dados completos e desbalanceados = CV [svm_pontuacoes_complet_d_best], Acurácia [svm_accuracy_complet_d_best] e F1-Score [report_svm_complet_d_dict_best = classification_report(y_train, y_svm_train_pred_complet_d_best, output_dict=True); f1_svm_complet_d_best = report_svm_complet_d_dict_best['macro avg']['f1-score']];

    **Dados balanceados, padronizados (aplicado nos kernels=["rbf", "linear" e "poly"]) e com os melhores hiperparâmetros**

    - Kernel = "rbf" = CV [svm_rbf_pontuacoes_complet], Acurácia [svm_rbf_accuracy_complet] e F1-Score [report_svm_rbf_complet_dict_best = classification_report(y_train_balanced, y_svm_rbf_train_pred_complet, output_dict=True); f1_svm_rbf_complet_best = report_svm_rbf_complet_dict_best['macro avg']['f1-score']];

    - Kernel = "linear" = CV [svm_l_pontuacoes_complet], Acurácia [svm_l_accuracy_complet] e F1-Score [report_svm_l_complet_dict_best = classification_report(y_train_balanced, y_svm_l_train_pred_complet, output_dict=True); f1_svm_l_complet_best = report_svm_l_complet_dict_best['macro avg']['f1-score']];

    - Kernel = "poly" = CV [svm_p_pontuacoes_complet], Acurácia [svm_p_accuracy_complet] e F1-Score [report_svm_p_complet_dict_best = classification_report(y_train_balanced, y_svm_p_train_pred_complet, output_dict=True); f1_svm_p_complet_best = report_svm_p_complet_dict_best['macro avg']['f1-score']];

    - Aplicação de hiperparâmetros no SVM com os dados desbalanceados e padronizados = CV [svm_pontuacoes_complet_best], Acurácia [svm_accuracy_complet_best] e F1-Score [report_svm_complet_dict_best = classification_report(y_train_balanced, y_svm_train_pred_complet_best, output_dict=True); f1_svm_complet_best = report_svm_complet_dict_best['macro avg']['f1-score']];

    **Cenário selecionado**
    **Dados desbalanceados e despadronizados**

    - Kernel = "rbf" = CV [svm_pontuacoes_select_dp], Acurácia [svm_accuracy_select_dp] e F1-Score [report_svm_select_dp_dict = classification_report(y_train, y_svm_train_pred_select_dp, output_dict=True); f1_svm_select_dp = report_svm_select_dp_dict['macro avg']['f1-score']];

    - Kernel = "linear" = CV [svm_l_pontuacoes_select_dp], Acurácia [svm_l_accuracy_select_dp] e F1-Score [report_svm_l_select_dp_dict = classification_report(y_train, y_svm_l_train_pred_select_dp, output_dict=True); f1_svm_l_select_dp = report_svm_l_select_dp_dict['macro avg']['f1-score']];

    - Kernel = "poly" = CV [svm_p_pontuacoes_select_dp], Acurácia [svm_p_accuracy_select_dp] e F1-Score [report_svm_p_select_dp_dict = classification_report(y_train, y_svm_p_train_pred_select_dp, output_dict=True); f1_svm_p_select_dp = report_svm_p_select_dp_dict['macro avg']['f1-score']];

    - Aplicação de hiperparâmetros no SVM com os dados completos e desbalanceados = CV [svm_pontuacoes_select_d_best], Acurácia [svm_accuracy_select_d_best] e F1-Score [report_svm_select_d_dict_best = classification_report(y_train, y_svm_train_pred_select_d_best, output_dict=True); f1_svm_select_d_best = report_svm_select_d_dict_best['macro avg']['f1-score']];

    **Dados balanceados, padronizados (aplicado nos kernels=["rbf", "linear" e "poly"]) e com os melhores hiperparâmetros**

    - Kernel = "rbf" = CV [svm_rbf_pontuacoes_select], Acurácia [svm_rbf_accuracy_select] e F1-Score [report_svm_rbf_select_dict_best = classification_report(y_train_balanced, y_svm_rbf_train_pred_select, output_dict=True); f1_svm_rbf_select_best = report_svm_rbf_select_dict_best['macro avg']['f1-score']];

    - Kernel = "linear" = CV [svm_l_pontuacoes_select], Acurácia [svm_l_accuracy_select] e F1-Score [report_svm_l_select_dict_best = classification_report(y_train_balanced, y_svm_l_train_pred_select, output_dict=True); f1_svm_l_select_best = report_svm_l_select_dict_best['macro avg']['f1-score']];

    - Kernel = "poly" = CV [svm_p_pontuacoes_select], Acurácia [svm_p_accuracy_select] e F1-Score [report_svm_p_select_dict_best = classification_report(y_train_balanced, y_svm_p_train_pred_select, output_dict=True); f1_svm_p_select_best = report_svm_p_select_dict_best['macro avg']['f1-score']];

    - Aplicação de hiperparâmetros no SVM com os dados desbalanceados e padronizados = CV [svm_pontuacoes_select_best], Acurácia [svm_accuracy_select_best] e F1-Score [report_svm_select_dict_best = classification_report(y_train_balanced, y_svm_train_pred_select_best, output_dict=True); f1_svm_select_best = report_svm_select_dict_best['macro avg']['f1-score']].