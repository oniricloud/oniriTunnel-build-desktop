cmake_minimum_required(VERSION 4.0)

find_package(cmake-pear REQUIRED PATHS node_modules/cmake-pear)

project(pear_appling C CXX ASM)


add_pear_appling(
  pear_appling
  ID "d5xqafujqx46hgeqeriuuyf1tdgxxgmdm9njijogrxcpc4exnkfy"
  LINK "pear://d5xqafujqx46hgeqeriuuyf1tdgxxgmdm9njijogrxcpc4exnkfy"
  NAME "Oniri"
  VERSION 1.1.0
  VERSION_COMPANY_NAME "OniriCloud"
  VERSION_PRODUCT_NAME "Oniri"
  AUTHOR "OniriCloud"
  DESCRIPTION "A secure, decentralized P2P tunneling application."

  MACOS_IDENTIFIER com.oniri.test
  MACOS_CATEGORY public.app-category.utilities
  # MACOS_SIGNING_IDENTITY "2718499D3FEA620C4E7BB467274BD07691CC2BDD"

  WINDOWS_SIGNING_SUBJECT "CN=TempBuildCert"
  WINDOWS_SIGNING_THUMBPRINT ""

  LINUX_CATEGORY Utility
)