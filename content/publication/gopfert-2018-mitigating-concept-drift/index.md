---
title: "Mitigating Concept Drift via Rejection"
date: 2018-01-01
publishDate: 2020-08-11T17:20:45.019701Z
authors: ["Jan Philip Göpfert", "Barbara Hammer", "Heiko Wersing"]
publication_types: ["1"]
abstract: "We extend two recent learning architectures for drift, the self-adjusting memory architecture (SAM-kNN) and adaptive random forests (ARF), to incorporate a reject option, resulting in highly competitive state-of-the-art technologies."
featured: true
publication: "*International Conference on Artificial Neural Networks*"
doi: "10.1007/978-3-030-01418-6_45"
url_pdf: "https://pub.uni-bielefeld.de/download/2921316/2921317/drift-reject-preprint.pdf"
---

Learning in non-stationary environments is challenging, because under such conditions the common assumption of independent and identically distributed data does not hold; when concept drift is present it necessitates continuous system updates. In recent years, several powerful approaches have been proposed. However, these models typically classify any input, regardless of their confidence in the classification – a strategy, which is not optimal, particularly in safety-critical environments where alternatives to a (possibly unclear) decision exist, such as additional tests or a short delay of the decision. Formally speaking, this alternative corresponds to classification with rejection, a strategy which seems particularly promising in the context of concept drift, i.e. the occurrence of situations where the current model is wrong due to a concept change. In this contribution, we propose to extend learning under concept drift with rejection. Specifically, we extend two recent learning architectures for drift, the self-adjusting memory architecture (SAM-kNN) and adaptive random forests (ARF), to incorporate a reject option, resulting in highly competitive state-of-the-art technologies. We evaluate their performance in learning scenarios with different types of drift.
