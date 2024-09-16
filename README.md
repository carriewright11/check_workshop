# README
# Acute Myeloid Leukemia Heatmap Analysis Documentation

This repository contains an analysis of acute myeloid leukemia (AML) using RNA-seq data from a study by Shih et al., 2017 [1]. The analysis was adapted from the refine.bio-examples notebook [2].

## Table of Contents
1. [Purpose of the Analysis](#purpose-of-the-analysis)
2. [Dataset Information](#dataset-information)
3. [Setup](#setup)
4. [Clustering Heatmap - RNA-seq](#clustering-heatmap---RNA-seq)
   1. [Install Libraries](#install-libraries)
   2. [Import and Setup Data](#import-and-setup-data)
   3. [Choose Genes of Interest](#choose-genes-of-interest)
   4. [Prepare Metadata for Annotation](#prepare-metadata-for-annotation)
   5. [Create Annotated Heatmap](#create-annotated-heatmap)
   6. [Save Heatmap](#save-heatmap)
5. [Session Info](#session-info)

## Purpose of the Analysis

This analysis uses RNA-seq data from 19 acute myeloid leukemia samples obtained from mice. The dataset contains RNA-sequence results for types of AML under controlled treatment conditions [1].

## Dataset Information

- Source: Shih et al., 2017 [1]
- Provider: refine.bio [2]
- Number of samples: 19
- Data type: RNA-seq
- Pre-processing: Quantile normalized by refine.bio [2]

## Setup

Before running the analysis, ensure you have the necessary libraries installed. You'll need `pheatmap` and `magrittr`.

