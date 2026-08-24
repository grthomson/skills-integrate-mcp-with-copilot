BuildNext(STRING currentVersion, STRING previousVersion) :=
    ChangeService.WIP.UKLexIDChangeServiceRegressionTests_newChangeTypes.BuildRidFile(
        currentVersion,
        previousVersion,
        ridFile_path(currentVersion),
        ridFile_path(previousVersion),
        '',
        ''
    );

    SEQUENTIAL(
    BuildNext('20250802', '20250718'),
    BuildNext('20250815', '20250802'),
    BuildNext('20250829', '20250815'),
    BuildNext('20250912', '20250829'),
    BuildNext('20250926', '20250912'),
    BuildNext('20251010', '20250926'),
    BuildNext('20251024', '20251010'),
    BuildNext('20251107', '20251024'),
    BuildNext('20251121', '20251107'),
    BuildNext('20251205', '20251121'),
    BuildNext('20251222', '20251205'),
    BuildNext('20260102', '20251222'),
    BuildNext('20260116', '20260102'),
    BuildNext('20260130', '20260116'),
    BuildNext('20260213', '20260130'),
    BuildNext('20260302', '20260213'),
    BuildNext('20260313', '20260302'),
    BuildNext('20260327', '20260313'),
    BuildNext('20260410', '20260327'),
    BuildNext('20260424', '20260410'),
    BuildNext('20260507', '20260424'),
    BuildNext('20260522', '20260507'),
    BuildNext('20260605', '20260522'),
    BuildNext('20260618', '20260605'),
    BuildNext('20260703', '20260618')
);