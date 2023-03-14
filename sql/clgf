-- phpMyAdmin SQL Dump
-- version 5.2.0
-- https://www.phpmyadmin.net/
--
-- Host: 127.0.0.1
-- Generation Time: Jan 20, 2023 at 07:47 AM
-- Server version: 10.4.25-MariaDB
-- PHP Version: 8.1.10

SET SQL_MODE = "NO_AUTO_VALUE_ON_ZERO";
START TRANSACTION;
SET time_zone = "+00:00";


/*!40101 SET @OLD_CHARACTER_SET_CLIENT=@@CHARACTER_SET_CLIENT */;
/*!40101 SET @OLD_CHARACTER_SET_RESULTS=@@CHARACTER_SET_RESULTS */;
/*!40101 SET @OLD_COLLATION_CONNECTION=@@COLLATION_CONNECTION */;
/*!40101 SET NAMES utf8mb4 */;

--
-- Database: `clgf`
--

-- --------------------------------------------------------

--
-- Table structure for table `accounts`
--

CREATE TABLE `accounts` (
  `id` int(11) NOT NULL,
  `username` varchar(50) NOT NULL,
  `password` varchar(255) NOT NULL,
  `name` text NOT NULL,
  `access` text NOT NULL,
  `phone` varchar(11) NOT NULL,
  `accID` text NOT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4;

--
-- Dumping data for table `accounts`
--

INSERT INTO `accounts` (`id`, `username`, `password`, `name`, `access`, `phone`, `accID`) VALUES
(9, 'cliff', '$2y$10$XEJk5nsJTcqo2siPIB0BiujPx7W2sSXGpTtwBDtkq1bw57y8SR1Aa', 'cliff', 'admin', '0', ''),
(19, 'meme', '$2y$10$f4gyZc.yfmwDHswY6B6V/eSCrMYrUiD3BhMyJwULTuF6iaFuAMxoe', 'meme', 'admin', '918031920', 'ADMIN0002'),
(20, 'moya', '$2y$10$1zVLjF9ZD.f/V86NB8GvVe6qh7iCHJJu6VY6uSrko3YiLS7M0XUJW', 'moya', 'admin', '2147483647', 'ADMIN0003'),
(21, 'kokey', '$2y$10$O0MQu6jijYi/81iRhkf2EuPdo/qXJ4AMFpyWUozq1tbHJlvAFnzXO', 'KALBO', 'admin', '2147483647', 'ADMIN0004'),
(22, 'gina', '$2y$10$EbxbnAn8AGoBq6IiyM5m0.gdKyLJjrrEjQScUFqu1iRTlhBGORJpC', 'GINA', 'user', '2147483647', 'USER0005'),
(23, 'jay', '$2y$10$mxzm7R00AJ1CaHjfvJQuj.mmqJVBaNR3VpSW5rgzruI6DO3t0EaWe', 'JAY MOYA', 'admin', '2147483647', 'ADMIN0006'),
(24, 'username', '$2y$10$dpB9.MINU1Zzu1KpBakU.uobI6KGhftxAZOw896YPPvV6cryYp7hm', 'JAY MOYA', 'admin', '2147483647', 'ADMIN0007'),
(25, 'admins', '$2y$10$9zFLwWDioteDnaK1.a4U8eLcp5F1Vw2Y6.L1MO7aOgG1CtJKtFlzu', 'Jay Cobb', 'admin', '09669230414', 'ADMIN0008'),
(26, 'hardwellmoya', '$2y$10$vyxVnPUY9xbIXmzfPS/Q3u1xnHfbaByj/T8UAHwtFCMLpiuuekWju', 'moya', 'admin', '09232324232', 'ADMIN0009'),
(27, 'moya', '$2y$10$sM8oRA1hbp0IYL2Sas1uW.EYATWpZo4ZZVIpdqzMIeSegO8xT0.Te', 'KOBE', 'user', '08231312312', 'USER0010'),
(28, 'kobe', '$2y$10$ScLfpxG4kGvUrhWp38C8vu9jEeitP2Wgd/235S.Z7KMEgZ8IBcpSm', 'moya', 'user', '09213213211', 'USER0011'),
(29, 'paras', '$2y$10$J6oN.2PWYfcY7qYBIa72ROCLOlkt94UrMaotTCyypzj//QumfG4xG', 'kobe paras', 'user', '0933232323', 'USER0012');

-- --------------------------------------------------------

--
-- Table structure for table `attendance`
--

CREATE TABLE `attendance` (
  `attendanceid` varchar(50) NOT NULL,
  `stype` varchar(50) NOT NULL,
  `sdate` date NOT NULL,
  `stime` text NOT NULL,
  `attendancelist` text NOT NULL,
  `id` int(11) NOT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4;

--
-- Dumping data for table `attendance`
--

INSERT INTO `attendance` (`attendanceid`, `stype`, `sdate`, `stime`, `attendancelist`, `id`) VALUES
('SF00012022', 'Sunday Fellowship', '2022-12-26', '8:50:42 PM', '[{\"memID\":\"\",\"name\":\"\",\"category\":\"\",\"attendance\":false,\"email\":\"\"},{\"memID\":\"HYPE0001\",\"name\":\"Jan Ryan A.  Divinagracia\",\"category\":\"hype\",\"attendance\":true,\"email\":\"janryanadivinagracia25@gmail.com\"},{\"memID\":\"JKIDS0002\",\"name\":\"JayCobb Andrew  Moya\",\"category\":\"jkids\",\"attendance\":false,\"email\":\"Jaycobb1901@gmail.com\"},{\"memID\":\"Y80003\",\"name\":\"John Cliff  Fortaleza\",\"category\":\"yadults\",\"attendance\":false,\"email\":\"Uvuvwefor1@gmail.com\"}]', 5),
('SF00022022', 'Sunday Fellowship', '2022-12-26', '9:06:07 PM', '[{\"memID\":\"HYPE0001\",\"name\":\"Jan Ryan A.  Divinagracia\",\"category\":\"hype\",\"attendance\":true,\"email\":\"janryanadivinagracia25@gmail.com\"},{\"memID\":\"JKIDS0002\",\"name\":\"JayCobb Andrew  Moya\",\"category\":\"jkids\",\"attendance\":false,\"email\":\"Jaycobb1901@gmail.com\"},{\"memID\":\"Y80003\",\"name\":\"John Cliff  Fortaleza\",\"category\":\"yadults\",\"attendance\":false,\"email\":\"Uvuvwefor1@gmail.com\"}]', 15),
('SF00032022', 'Sunday Fellowship', '2022-12-26', '9:07:32 PM', '[{\"memID\":\"HYPE0001\",\"name\":\"Jan Ryan A.  Divinagracia\",\"category\":\"hype\",\"attendance\":true,\"email\":\"janryanadivinagracia25@gmail.com\"},{\"memID\":\"JKIDS0002\",\"name\":\"JayCobb Andrew  Moya\",\"category\":\"jkids\",\"attendance\":true,\"email\":\"Jaycobb1901@gmail.com\"},{\"memID\":\"Y80003\",\"name\":\"John Cliff  Fortaleza\",\"category\":\"yadults\",\"attendance\":false,\"email\":\"Uvuvwefor1@gmail.com\"}]', 16),
('SF00042022', 'Sunday Fellowship', '2022-12-26', '9:17:56 PM', '[{\"memID\":\"HYPE0001\",\"name\":\"Jan Ryan A.  Divinagracia\",\"category\":\"hype\",\"attendance\":false,\"email\":\"janryanadivinagracia25@gmail.com\"},{\"memID\":\"JKIDS0002\",\"name\":\"JayCobb Andrew  Moya\",\"category\":\"jkids\",\"attendance\":true,\"email\":\"Jaycobb1901@gmail.com\"},{\"memID\":\"Y80003\",\"name\":\"John Cliff  Fortaleza\",\"category\":\"yadults\",\"attendance\":false,\"email\":\"Uvuvwefor1@gmail.com\"}]', 19),
('SF00052022', 'Sunday Fellowship', '2022-12-26', '9:27:54 PM', '[{\"memID\":\"HYPE0001\",\"name\":\"Jan Ryan A.  Divinagracia\",\"category\":\"hype\",\"attendance\":true,\"email\":\"janryanadivinagracia25@gmail.com\"},{\"memID\":\"JKIDS0002\",\"name\":\"JayCobb Andrew  Moya\",\"category\":\"jkids\",\"attendance\":false,\"email\":\"Jaycobb1901@gmail.com\"},{\"memID\":\"Y80003\",\"name\":\"John Cliff  Fortaleza\",\"category\":\"yadults\",\"attendance\":false,\"email\":\"Uvuvwefor1@gmail.com\"}]', 20),
('SF00062022', 'Sunday Fellowship', '2022-12-26', '11:18:56 PM', '[{\"memID\":\"HYPE0001\",\"name\":\"Jan Ryan A.  Divinagracia\",\"category\":\"hype\",\"attendance\":false,\"email\":\"janryanadivinagracia25@gmail.com\"},{\"memID\":\"JKIDS0002\",\"name\":\"JayCobb Andrew  Moya\",\"category\":\"jkids\",\"attendance\":true,\"email\":\"Jaycobb1901@gmail.com\"},{\"memID\":\"Y80003\",\"name\":\"John Cliff  Fortaleza\",\"category\":\"yadults\",\"attendance\":true,\"email\":\"Uvuvwefor1@gmail.com\"}]', 21),
('SF00072022', 'Sunday Fellowship', '2022-12-26', '11:21:05 PM', '[{\"memID\":\"HYPE0001\",\"name\":\"Jan Ryan A.  Divinagracia\",\"category\":\"hype\",\"attendance\":false,\"email\":\"janryanadivinagracia25@gmail.com\"},{\"memID\":\"JKIDS0002\",\"name\":\"JayCobb Andrew  Moya\",\"category\":\"jkids\",\"attendance\":true,\"email\":\"Jaycobb1901@gmail.com\"}]', 22),
('SF00082022', 'Sunday Fellowship', '2022-12-27', '1:05:29 AM', '[{\"memID\":\"HYPE0001\",\"name\":\"Jan Ryan A.  Divinagracia\",\"category\":\"hype\",\"attendance\":false,\"email\":\"janryanadivinagracia25@gmail.com\"},{\"memID\":\"JKIDS0002\",\"name\":\"JayCobb Andrew  Moya\",\"category\":\"jkids\",\"attendance\":false,\"email\":\"Jaycobb1901@gmail.com\"},{\"memID\":\"Y80003\",\"name\":\"John Cliff  Fortaleza\",\"category\":\"yadults\",\"attendance\":false,\"email\":\"Uvuvwefor1@gmail.com\"}]', 23),
('SF00092022', 'Sunday Fellowship', '2022-12-27', '1:07:41 AM', '[{\"memID\":\"HYPE0001\",\"name\":\"Jan Ryan A.  Divinagracia\",\"category\":\"hype\",\"attendance\":false,\"email\":\"janryanadivinagracia25@gmail.com\"},{\"memID\":\"JKIDS0002\",\"name\":\"JayCobb Andrew  Moya\",\"category\":\"jkids\",\"attendance\":true,\"email\":\"Jaycobb1901@gmail.com\"},{\"memID\":\"Y80003\",\"name\":\"John Cliff  Fortaleza\",\"category\":\"yadults\",\"attendance\":true,\"email\":\"Uvuvwefor1@gmail.com\"}]', 24),
('SF00102022', 'Sunday Fellowship', '2022-12-27', '1:07:52 AM', '[{\"memID\":\"HYPE0001\",\"name\":\"Jan Ryan A.  Divinagracia\",\"category\":\"hype\",\"attendance\":false,\"email\":\"janryanadivinagracia25@gmail.com\"},{\"memID\":\"JKIDS0002\",\"name\":\"JayCobb Andrew  Moya\",\"category\":\"jkids\",\"attendance\":false,\"email\":\"Jaycobb1901@gmail.com\"},{\"memID\":\"Y80003\",\"name\":\"John Cliff  Fortaleza\",\"category\":\"yadults\",\"attendance\":false,\"email\":\"Uvuvwefor1@gmail.com\"}]', 25),
('SF00112022', 'Sunday Fellowship', '2022-12-27', '11:54:22 AM', '[{\"memID\":\"HYPE0001\",\"name\":\"Jan Ryan A.  Divinagracia\",\"category\":\"hype\",\"attendance\":true,\"email\":\"janryanadivinagracia25@gmail.com\"},{\"memID\":\"JKIDS0002\",\"name\":\"JayCobb Andrew  Moya\",\"category\":\"jkids\",\"attendance\":true,\"email\":\"Jaycobb1901@gmail.com\"},{\"memID\":\"Y80003\",\"name\":\"John Cliff  Fortaleza\",\"category\":\"yadults\",\"attendance\":true,\"email\":\"Uvuvwefor1@gmail.com\"}]', 26),
('SF00122022', 'Sunday Fellowship', '2022-12-27', '4:02:39 PM', '[{\"memID\":\"HYPE0001\",\"name\":\"Jan Ryan A.  Divinagracia\",\"category\":\"hype\",\"attendance\":false,\"email\":\"janryanadivinagracia25@gmail.com\"},{\"memID\":\"HYPE0004\",\"name\":\"sadas dasd sadas\",\"category\":\"hype\",\"attendance\":false,\"email\":\"dsadasdsa\"},{\"memID\":\"JKIDS0002\",\"name\":\"JayCobb Andrew  Moya\",\"category\":\"jkids\",\"attendance\":false,\"email\":\"Jaycobb1901@gmail.com\"},{\"memID\":\"Y80003\",\"name\":\"John Cliff  Fortaleza\",\"category\":\"yadults\",\"attendance\":false,\"email\":\"Uvuvwefor1@gmail.com\"}]', 27),
('SF00132022', 'Sunday Fellowship', '2022-12-27', '8:30:49 PM', '[{\"memID\":\"HYPE0001\",\"name\":\"Jan Ryan A.  Divinagracia\",\"category\":\"hype\",\"attendance\":true,\"email\":\"janryanadivinagracia25@gmail.com\"},{\"memID\":\"HYPE0004\",\"name\":\"sadas dasd sadas\",\"category\":\"hype\",\"attendance\":true,\"email\":\"dsadasdsa\"},{\"memID\":\"JKIDS0002\",\"name\":\"JayCobb Andrew  Moya\",\"category\":\"jkids\",\"attendance\":true,\"email\":\"Jaycobb1901@gmail.com\"},{\"memID\":\"Y80003\",\"name\":\"John Cliff  Fortaleza\",\"category\":\"yadults\",\"attendance\":true,\"email\":\"Uvuvwefor1@gmail.com\"}]', 28),
('SF00142022', 'Sunday Fellowship', '2022-12-27', '8:33:29 PM', '[{\"memID\":\"HYPE0001\",\"name\":\"Jan Ryan A.  Divinagracia\",\"category\":\"hype\",\"attendance\":false,\"email\":\"janryanadivinagracia25@gmail.com\"},{\"memID\":\"HYPE0004\",\"name\":\"sadas dasd sadas\",\"category\":\"hype\",\"attendance\":false,\"email\":\"dsadasdsa\"},{\"memID\":\"JKIDS0002\",\"name\":\"JayCobb Andrew  Moya\",\"category\":\"jkids\",\"attendance\":false,\"email\":\"Jaycobb1901@gmail.com\"},{\"memID\":\"Y80003\",\"name\":\"John Cliff  Fortaleza\",\"category\":\"yadults\",\"attendance\":true,\"email\":\"Uvuvwefor1@gmail.com\"},{\"memID\":\"Y80005\",\"name\":\"Zairie G Belllin\",\"category\":\"yadults\",\"attendance\":true,\"email\":\"zarie@gmail.com\"}]', 29),
('SF00152022', 'General Event', '2022-12-27', '9:19:28 PM', '[{\"memID\":\"ADULTS0006\",\"name\":\"Kobe B Bryant\",\"category\":\"mens\",\"attendance\":true,\"email\":\"kobe@gmail.com\"},{\"memID\":\"ADULTS0007\",\"name\":\"Kokoy D Baldo\",\"category\":\"mens\",\"attendance\":true,\"email\":\"asdasd@gmail.com\"},{\"memID\":\"HYPE0001\",\"name\":\"Jan Ryan A.  Divinagracia\",\"category\":\"hype\",\"attendance\":true,\"email\":\"janryanadivinagracia25@gmail.com\"},{\"memID\":\"HYPE0004\",\"name\":\"sadas dasd sadas\",\"category\":\"hype\",\"attendance\":true,\"email\":\"dsadasdsa\"},{\"memID\":\"JKIDS0002\",\"name\":\"JayCobb Andrew  Moya\",\"category\":\"jkids\",\"attendance\":true,\"email\":\"Jaycobb1901@gmail.com\"},{\"memID\":\"JKIDS0008\",\"name\":\"adsasdsadsa adssa dasd\",\"category\":\"jkids\",\"attendance\":true,\"email\":\"asdsa\"},{\"memID\":\"JKIDS0010\",\"name\":\"asdax123exwsa sd 123xsad\",\"category\":\"jkids\",\"attendance\":true,\"email\":\"asd\"},{\"memID\":\"Y80003\",\"name\":\"John Cliff  Fortaleza\",\"category\":\"yadults\",\"attendance\":true,\"email\":\"Uvuvwefor1@gmail.com\"},{\"memID\":\"Y80005\",\"name\":\"Zairie G Belllin\",\"category\":\"yadults\",\"attendance\":true,\"email\":\"zarie@gmail.com\"},{\"memID\":\"Y80009\",\"name\":\"asdasd ds asd12\",\"category\":\"yadults\",\"attendance\":true,\"email\":\"\"}]', 30),
('SF00162022', 'Sunday Fellowship', '2022-12-27', '9:19:40 PM', '[{\"memID\":\"ADULTS0006\",\"name\":\"Kobe B Bryant\",\"category\":\"mens\",\"attendance\":true,\"email\":\"kobe@gmail.com\"},{\"memID\":\"ADULTS0007\",\"name\":\"Kokoy D Baldo\",\"category\":\"mens\",\"attendance\":true,\"email\":\"asdasd@gmail.com\"},{\"memID\":\"HYPE0001\",\"name\":\"Jan Ryan A.  Divinagracia\",\"category\":\"hype\",\"attendance\":true,\"email\":\"janryanadivinagracia25@gmail.com\"},{\"memID\":\"HYPE0004\",\"name\":\"sadas dasd sadas\",\"category\":\"hype\",\"attendance\":true,\"email\":\"dsadasdsa\"},{\"memID\":\"JKIDS0002\",\"name\":\"JayCobb Andrew  Moya\",\"category\":\"jkids\",\"attendance\":true,\"email\":\"Jaycobb1901@gmail.com\"},{\"memID\":\"JKIDS0008\",\"name\":\"adsasdsadsa adssa dasd\",\"category\":\"jkids\",\"attendance\":false,\"email\":\"asdsa\"},{\"memID\":\"JKIDS0010\",\"name\":\"asdax123exwsa sd 123xsad\",\"category\":\"jkids\",\"attendance\":false,\"email\":\"asd\"},{\"memID\":\"Y80003\",\"name\":\"John Cliff  Fortaleza\",\"category\":\"yadults\",\"attendance\":false,\"email\":\"Uvuvwefor1@gmail.com\"},{\"memID\":\"Y80005\",\"name\":\"Zairie G Belllin\",\"category\":\"yadults\",\"attendance\":false,\"email\":\"zarie@gmail.com\"},{\"memID\":\"Y80009\",\"name\":\"asdasd ds asd12\",\"category\":\"yadults\",\"attendance\":false,\"email\":\"\"}]', 31),
('SF00172022', 'Sunday Fellowship', '2022-12-27', '9:21:15 PM', '[{\"memID\":\"ADULTS0006\",\"name\":\"Kobe B Bryant\",\"category\":\"mens\",\"attendance\":true,\"email\":\"kobe@gmail.com\"},{\"memID\":\"ADULTS0007\",\"name\":\"Kokoy D Baldo\",\"category\":\"mens\",\"attendance\":true,\"email\":\"asdasd@gmail.com\"},{\"memID\":\"HYPE0001\",\"name\":\"Jan Ryan A.  Divinagracia\",\"category\":\"hype\",\"attendance\":true,\"email\":\"janryanadivinagracia25@gmail.com\"},{\"memID\":\"HYPE0004\",\"name\":\"sadas dasd sadas\",\"category\":\"hype\",\"attendance\":true,\"email\":\"dsadasdsa\"},{\"memID\":\"JKIDS0002\",\"name\":\"JayCobb Andrew  Moya\",\"category\":\"jkids\",\"attendance\":true,\"email\":\"Jaycobb1901@gmail.com\"},{\"memID\":\"JKIDS0008\",\"name\":\"adsasdsadsa adssa dasd\",\"category\":\"jkids\",\"attendance\":true,\"email\":\"asdsa\"},{\"memID\":\"JKIDS0010\",\"name\":\"asdax123exwsa sd 123xsad\",\"category\":\"jkids\",\"attendance\":true,\"email\":\"asd\"},{\"memID\":\"Y80003\",\"name\":\"John Cliff  Fortaleza\",\"category\":\"yadults\",\"attendance\":true,\"email\":\"Uvuvwefor1@gmail.com\"},{\"memID\":\"Y80005\",\"name\":\"Zairie G Belllin\",\"category\":\"yadults\",\"attendance\":false,\"email\":\"zarie@gmail.com\"},{\"memID\":\"Y80009\",\"name\":\"asdasd ds asd12\",\"category\":\"yadults\",\"attendance\":false,\"email\":\"\"}]', 32),
('SF00182022', 'Sunday Fellowship', '2022-12-27', '9:45:40 PM', '[{\"memID\":\"ADULTS0006\",\"name\":\"Kobe B Bryant\",\"category\":\"mens\",\"attendance\":true,\"email\":\"kobe@gmail.com\"},{\"memID\":\"ADULTS0007\",\"name\":\"Kokoy D Baldo\",\"category\":\"mens\",\"attendance\":true,\"email\":\"asdasd@gmail.com\"}]', 33),
('SF00192023', 'General Event', '2023-01-17', '6:38:52 PM', '[{\"memID\":\"ADULTS0006\",\"name\":\"Kobe B Bryant\",\"category\":\"mens\",\"attendance\":false,\"email\":\"kobe@gmail.com\"},{\"memID\":\"ADULTS0007\",\"name\":\"Kokoy D Baldo\",\"category\":\"mens\",\"attendance\":false,\"email\":\"asdasd@gmail.com\"},{\"memID\":\"HYPE0001\",\"name\":\"Jan Ryan A.  Divinagracia\",\"category\":\"hype\",\"attendance\":true,\"email\":\"janryanadivinagracia25@gmail.com\"},{\"memID\":\"HYPE0004\",\"name\":\"sadas dasd sadas\",\"category\":\"hype\",\"attendance\":false,\"email\":\"dsadasdsa\"},{\"memID\":\"JKIDS0002\",\"name\":\"JayCobb Andrew  Moya\",\"category\":\"jkids\",\"attendance\":false,\"email\":\"Jaycobb1901@gmail.com\"},{\"memID\":\"JKIDS0008\",\"name\":\"adsasdsadsa adssa dasd\",\"category\":\"jkids\",\"attendance\":false,\"email\":\"asdsa\"},{\"memID\":\"JKIDS0010\",\"name\":\"asdax123exwsa sd 123xsad\",\"category\":\"jkids\",\"attendance\":false,\"email\":\"asd\"},{\"memID\":\"Y80003\",\"name\":\"John Cliff  Fortaleza\",\"category\":\"yadults\",\"attendance\":true,\"email\":\"Uvuvwefor1@gmail.com\"},{\"memID\":\"Y80005\",\"name\":\"Zairie G Belllin\",\"category\":\"yadults\",\"attendance\":false,\"email\":\"zarie@gmail.com\"},{\"memID\":\"Y80009\",\"name\":\"asdasd ds asd12\",\"category\":\"yadults\",\"attendance\":false,\"email\":\"\"}]', 34);

-- --------------------------------------------------------

--
-- Table structure for table `attendancelist`
--

CREATE TABLE `attendancelist` (
  `attendanceid` varchar(20) NOT NULL,
  `memname` text NOT NULL,
  `memid` varchar(50) NOT NULL,
  `category` text NOT NULL,
  `astatus` tinyint(1) NOT NULL,
  `id` int(11) NOT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4;

--
-- Dumping data for table `attendancelist`
--

INSERT INTO `attendancelist` (`attendanceid`, `memname`, `memid`, `category`, `astatus`, `id`) VALUES
('SF00012022', '', '', '', 0, 1),
('SF00012022', 'Jan Ryan A.  Divinagracia', 'HYPE0001', 'hype', 1, 2),
('SF00012022', 'JayCobb Andrew  Moya', 'JKIDS0002', 'jkids', 0, 3),
('SF00012022', 'John Cliff  Fortaleza', 'Y80003', 'yadults', 0, 4),
('SF00022022', 'Jan Ryan A.  Divinagracia', 'HYPE0001', 'hype', 1, 5),
('SF00022022', 'JayCobb Andrew  Moya', 'JKIDS0002', 'jkids', 0, 6),
('SF00022022', 'John Cliff  Fortaleza', 'Y80003', 'yadults', 0, 7),
('SF00032022', 'Jan Ryan A.  Divinagracia', 'HYPE0001', 'hype', 1, 8),
('SF00032022', 'JayCobb Andrew  Moya', 'JKIDS0002', 'jkids', 1, 9),
('SF00032022', 'John Cliff  Fortaleza', 'Y80003', 'yadults', 0, 10),
('SF00042022', 'Jan Ryan A.  Divinagracia', 'HYPE0001', 'hype', 0, 11),
('SF00042022', 'JayCobb Andrew  Moya', 'JKIDS0002', 'jkids', 1, 12),
('SF00042022', 'John Cliff  Fortaleza', 'Y80003', 'yadults', 0, 13),
('SF00052022', 'Jan Ryan A.  Divinagracia', 'HYPE0001', 'hype', 1, 14),
('SF00052022', 'JayCobb Andrew  Moya', 'JKIDS0002', 'jkids', 0, 15),
('SF00052022', 'John Cliff  Fortaleza', 'Y80003', 'yadults', 0, 16),
('SF00062022', 'Jan Ryan A.  Divinagracia', 'HYPE0001', 'hype', 0, 17),
('SF00062022', 'JayCobb Andrew  Moya', 'JKIDS0002', 'jkids', 1, 18),
('SF00062022', 'John Cliff  Fortaleza', 'Y80003', 'yadults', 1, 19),
('SF00072022', 'Jan Ryan A.  Divinagracia', 'HYPE0001', 'hype', 0, 20),
('SF00072022', 'JayCobb Andrew  Moya', 'JKIDS0002', 'jkids', 1, 21),
('SF00082022', 'Jan Ryan A.  Divinagracia', 'HYPE0001', 'hype', 0, 22),
('SF00082022', 'JayCobb Andrew  Moya', 'JKIDS0002', 'jkids', 0, 23),
('SF00082022', 'John Cliff  Fortaleza', 'Y80003', 'yadults', 0, 24),
('SF00092022', 'Jan Ryan A.  Divinagracia', 'HYPE0001', 'hype', 0, 25),
('SF00092022', 'JayCobb Andrew  Moya', 'JKIDS0002', 'jkids', 1, 26),
('SF00092022', 'John Cliff  Fortaleza', 'Y80003', 'yadults', 1, 27),
('SF00102022', 'Jan Ryan A.  Divinagracia', 'HYPE0001', 'hype', 0, 28),
('SF00102022', 'JayCobb Andrew  Moya', 'JKIDS0002', 'jkids', 0, 29),
('SF00102022', 'John Cliff  Fortaleza', 'Y80003', 'yadults', 0, 30),
('SF00112022', 'Jan Ryan A.  Divinagracia', 'HYPE0001', 'hype', 1, 31),
('SF00112022', 'JayCobb Andrew  Moya', 'JKIDS0002', 'jkids', 1, 32),
('SF00112022', 'John Cliff  Fortaleza', 'Y80003', 'yadults', 1, 33),
('SF00122022', 'Jan Ryan A.  Divinagracia', 'HYPE0001', 'hype', 0, 34),
('SF00122022', 'sadas dasd sadas', 'HYPE0004', 'hype', 0, 35),
('SF00122022', 'JayCobb Andrew  Moya', 'JKIDS0002', 'jkids', 0, 36),
('SF00122022', 'John Cliff  Fortaleza', 'Y80003', 'yadults', 0, 37),
('SF00132022', 'Jan Ryan A.  Divinagracia', 'HYPE0001', 'hype', 1, 38),
('SF00132022', 'sadas dasd sadas', 'HYPE0004', 'hype', 1, 39),
('SF00132022', 'JayCobb Andrew  Moya', 'JKIDS0002', 'jkids', 1, 40),
('SF00132022', 'John Cliff  Fortaleza', 'Y80003', 'yadults', 1, 41),
('SF00142022', 'Jan Ryan A.  Divinagracia', 'HYPE0001', 'hype', 0, 42),
('SF00142022', 'sadas dasd sadas', 'HYPE0004', 'hype', 0, 43),
('SF00142022', 'JayCobb Andrew  Moya', 'JKIDS0002', 'jkids', 0, 44),
('SF00142022', 'John Cliff  Fortaleza', 'Y80003', 'yadults', 1, 45),
('SF00142022', 'Zairie G Belllin', 'Y80005', 'yadults', 1, 46),
('SF00152022', 'Kobe B Bryant', 'ADULTS0006', 'mens', 1, 47),
('SF00152022', 'Kokoy D Baldo', 'ADULTS0007', 'mens', 1, 48),
('SF00152022', 'Jan Ryan A.  Divinagracia', 'HYPE0001', 'hype', 1, 49),
('SF00152022', 'sadas dasd sadas', 'HYPE0004', 'hype', 1, 50),
('SF00152022', 'JayCobb Andrew  Moya', 'JKIDS0002', 'jkids', 1, 51),
('SF00152022', 'adsasdsadsa adssa dasd', 'JKIDS0008', 'jkids', 1, 52),
('SF00152022', 'asdax123exwsa sd 123xsad', 'JKIDS0010', 'jkids', 1, 53),
('SF00152022', 'John Cliff  Fortaleza', 'Y80003', 'yadults', 1, 54),
('SF00152022', 'Zairie G Belllin', 'Y80005', 'yadults', 1, 55),
('SF00152022', 'asdasd ds asd12', 'Y80009', 'yadults', 1, 56),
('SF00162022', 'Kobe B Bryant', 'ADULTS0006', 'mens', 1, 57),
('SF00162022', 'Kokoy D Baldo', 'ADULTS0007', 'mens', 1, 58),
('SF00162022', 'Jan Ryan A.  Divinagracia', 'HYPE0001', 'hype', 1, 59),
('SF00162022', 'sadas dasd sadas', 'HYPE0004', 'hype', 1, 60),
('SF00162022', 'JayCobb Andrew  Moya', 'JKIDS0002', 'jkids', 1, 61),
('SF00162022', 'adsasdsadsa adssa dasd', 'JKIDS0008', 'jkids', 0, 62),
('SF00162022', 'asdax123exwsa sd 123xsad', 'JKIDS0010', 'jkids', 0, 63),
('SF00162022', 'John Cliff  Fortaleza', 'Y80003', 'yadults', 0, 64),
('SF00162022', 'Zairie G Belllin', 'Y80005', 'yadults', 0, 65),
('SF00162022', 'asdasd ds asd12', 'Y80009', 'yadults', 0, 66),
('SF00172022', 'Kobe B Bryant', 'ADULTS0006', 'mens', 1, 67),
('SF00172022', 'Kokoy D Baldo', 'ADULTS0007', 'mens', 1, 68),
('SF00172022', 'Jan Ryan A.  Divinagracia', 'HYPE0001', 'hype', 1, 69),
('SF00172022', 'sadas dasd sadas', 'HYPE0004', 'hype', 1, 70),
('SF00172022', 'JayCobb Andrew  Moya', 'JKIDS0002', 'jkids', 1, 71),
('SF00172022', 'adsasdsadsa adssa dasd', 'JKIDS0008', 'jkids', 1, 72),
('SF00172022', 'asdax123exwsa sd 123xsad', 'JKIDS0010', 'jkids', 1, 73),
('SF00172022', 'John Cliff  Fortaleza', 'Y80003', 'yadults', 1, 74),
('SF00172022', 'Zairie G Belllin', 'Y80005', 'yadults', 0, 75),
('SF00172022', 'asdasd ds asd12', 'Y80009', 'yadults', 0, 76),
('SF00182022', 'Kobe B Bryant', 'ADULTS0006', 'mens', 1, 77),
('SF00182022', 'Kokoy D Baldo', 'ADULTS0007', 'mens', 1, 78),
('SF00192023', 'Kobe B Bryant', 'ADULTS0006', 'mens', 0, 79),
('SF00192023', 'Kokoy D Baldo', 'ADULTS0007', 'mens', 0, 80),
('SF00192023', 'Jan Ryan A.  Divinagracia', 'HYPE0001', 'hype', 1, 81),
('SF00192023', 'sadas dasd sadas', 'HYPE0004', 'hype', 0, 82),
('SF00192023', 'JayCobb Andrew  Moya', 'JKIDS0002', 'jkids', 0, 83),
('SF00192023', 'adsasdsadsa adssa dasd', 'JKIDS0008', 'jkids', 0, 84),
('SF00192023', 'asdax123exwsa sd 123xsad', 'JKIDS0010', 'jkids', 0, 85),
('SF00192023', 'John Cliff  Fortaleza', 'Y80003', 'yadults', 1, 86),
('SF00192023', 'Zairie G Belllin', 'Y80005', 'yadults', 0, 87),
('SF00192023', 'asdasd ds asd12', 'Y80009', 'yadults', 0, 88);

-- --------------------------------------------------------

--
-- Table structure for table `members`
--

CREATE TABLE `members` (
  `id` int(11) NOT NULL,
  `memID` text NOT NULL,
  `fname` text NOT NULL,
  `mname` text NOT NULL,
  `lname` text NOT NULL,
  `suffix` text NOT NULL,
  `fullname` varchar(200) NOT NULL,
  `address` text NOT NULL,
  `stats` text NOT NULL,
  `age` int(3) NOT NULL,
  `dob` text NOT NULL,
  `gender` text NOT NULL,
  `email` text NOT NULL,
  `phone` text NOT NULL,
  `category` text NOT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4;

--
-- Dumping data for table `members`
--

INSERT INTO `members` (`id`, `memID`, `fname`, `mname`, `lname`, `suffix`, `fullname`, `address`, `stats`, `age`, `dob`, `gender`, `email`, `phone`, `category`) VALUES
(1, 'HYPE0001', 'Jan Ryan', 'A. ', 'Divinagracia', '', 'Jan Ryan A.  Divinagracia', '', '', 0, '', '', 'janryanadivinagracia25@gmail.com', '', 'hype'),
(2, 'JKIDS0002', 'JayCobb Andrew', '', 'Moya', '', 'JayCobb Andrew  Moya', '', '', 0, '', '', 'Jaycobb1901@gmail.com', '', 'jkids'),
(3, 'Y80003', 'John Cliff', '', 'Fortaleza', '', 'John Cliff  Fortaleza', '', '', 0, '', '', 'Uvuvwefor1@gmail.com', '', 'yadults'),
(4, 'HYPE0004', 'sadas', 'dasd', 'sadas', 'sr', 'sadas dasd sadas', '', 'Married', 0, '2022-12-01', 'Male', 'dsadasdsa', '12312', 'hype'),
(5, 'Y80005', 'Zairie', 'G', 'Belllin', 'N/A', 'Zairie G Belllin', 'asd', 'Single', 0, '2022-02-24', 'Female', 'zarie@gmail.com', '09669230414', 'yadults'),
(6, 'ADULTS0006', 'Kobe', 'B', 'Bryant', 'N/A', 'Kobe B Bryant', 'Bacolod City', 'Married', 0, '2022-12-08', 'Male', 'kobe@gmail.com', '09669230414', 'mens'),
(7, 'ADULTS0007', 'Kokoy', 'D', 'Baldo', 'jr', 'Kokoy D Baldo', 'asdasdsad', 'Single', 0, '2022-11-30', 'Male', 'asdasd@gmail.com', '00239923929', 'mens'),
(8, 'JKIDS0008', 'adsasdsadsa', 'adssa', 'dasd', 'sr', 'adsasdsadsa adssa dasd', 'das', 'Married', 0, '2022-12-02', 'Female', 'asdsa', '2132131', 'jkids'),
(9, 'Y80009', 'asdasd', 'ds', 'asd12', 'jr', 'asdasd ds asd12', '', 'Married', 0, '', 'Male', '', '', 'yadults'),
(10, 'JKIDS0010', 'asdax123exwsa', 'sd', '123xsad', 'III', 'asdax123exwsa sd 123xsad', 'asdas', 'Married', 0, '', 'Female', 'asd', '09669230414', 'jkids'),
(11, 'Y80011', 'asdsad', 'sdsad', 'sada', 'sr', 'asdsad sdsad sada', 'dsa', 'Married', 0, '2022-12-01', 'Female', 'asd', '123123', 'yadults');

--
-- Indexes for dumped tables
--

--
-- Indexes for table `accounts`
--
ALTER TABLE `accounts`
  ADD PRIMARY KEY (`id`);

--
-- Indexes for table `attendance`
--
ALTER TABLE `attendance`
  ADD PRIMARY KEY (`id`),
  ADD UNIQUE KEY `attendanceid` (`attendanceid`);

--
-- Indexes for table `attendancelist`
--
ALTER TABLE `attendancelist`
  ADD PRIMARY KEY (`id`),
  ADD KEY `attendanceid` (`attendanceid`),
  ADD KEY `attendaceid` (`attendanceid`),
  ADD KEY `memberid` (`memid`);

--
-- Indexes for table `members`
--
ALTER TABLE `members`
  ADD PRIMARY KEY (`id`);

--
-- AUTO_INCREMENT for dumped tables
--

--
-- AUTO_INCREMENT for table `accounts`
--
ALTER TABLE `accounts`
  MODIFY `id` int(11) NOT NULL AUTO_INCREMENT, AUTO_INCREMENT=30;

--
-- AUTO_INCREMENT for table `attendance`
--
ALTER TABLE `attendance`
  MODIFY `id` int(11) NOT NULL AUTO_INCREMENT, AUTO_INCREMENT=35;

--
-- AUTO_INCREMENT for table `attendancelist`
--
ALTER TABLE `attendancelist`
  MODIFY `id` int(11) NOT NULL AUTO_INCREMENT, AUTO_INCREMENT=89;

--
-- AUTO_INCREMENT for table `members`
--
ALTER TABLE `members`
  MODIFY `id` int(11) NOT NULL AUTO_INCREMENT, AUTO_INCREMENT=12;
COMMIT;

/*!40101 SET CHARACTER_SET_CLIENT=@OLD_CHARACTER_SET_CLIENT */;
/*!40101 SET CHARACTER_SET_RESULTS=@OLD_CHARACTER_SET_RESULTS */;
/*!40101 SET COLLATION_CONNECTION=@OLD_COLLATION_CONNECTION */;
