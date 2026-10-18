# ScamShield — AI-Powered Mobile Money Fraud Detection

**Team QuantumCrew | IBM Z Datathon 2026**

## Project Overview

ScamShield is a machine learning-based fraud detection prototype developed using **IBM LinuxONE**. It analyzes mobile money transactions to identify suspicious activity and support faster, risk-based decisions.

The system provides three possible outcomes:

- **APPROVE:** Allow low-risk transactions.
- **STEP_UP:** Request additional verification.
- **HOLD:** Flag high-risk transactions for investigation.

## Technologies Used

- **Python, Pandas, NumPy**
- **Machine Learning:** IBM Snap ML, LightGBM, scikit-learn, Isolation Forest
- **Platform:** IBM LinuxONE (s390x)
- **Development:** Jupyter Notebook
- **Dataset:** PaySim (6.36 million synthetic transactions)

## Key Results

| Metric | Result |
|---|---|
| Fraud detected or challenged | 83.3% |
| Fraud value stopped or challenged | 71.0% |
| Median decision latency | ~2.4 ms |
| Genuine transactions held | 0.7 per 10,000 |

*Results are based on synthetic data and simulated transaction replay.*

## Team Members

| Name | Contribution |
|---|---|
| **Maksuda Akther Tumpa** | Project Lead, Research, Planning, Testing |
| **Mohammad Fahim Uddin Alvi** | ML Development, Model Evaluation, IBM LinuxONE |
| **Hasin Sahad Haque** | Presentation and Documentation |
| **Pan Hui Xin** | Demo Video Production |
| **Khin Saw Win** | Demo Recording and Editing |

## Project Resources

- [PaySim Dataset](https://www.kaggle.com/datasets/ealaxi/paysim1)
- [IBM Snap ML](https://www.ibm.com/docs/en/watsonx/saas?topic=services-snap-machine-learning)
- [Scikit-learn](https://scikit-learn.org/)

## Future Improvements

Improve fraud detection accuracy, reduce false alarms, and explore integration with real-time financial transaction systems.

---

**Developed by Team QuantumCrew for IBM Z Datathon 2026.**
