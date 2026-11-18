# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '9dbe42fa448cb2ac35845f4a39244e4aa1f775ad',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '90c37f2ffdb6531a27eaf90f05983a549691761e',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '50184103b19027f5c7080060712d6a9470cf59ee',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '727277f679857e5a680cf559586268b2df35c48d',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'b26454f3ccd67e704117a39295fa13935fd3804c',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '71833aaa9d5c51329b898d82b2b0194f670c2ff6',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '1d3fbab1ff5abce9f3eb9f3e7fcf66f455ae4475',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '1b1e6773b3e00269a67d2d83d9268513d8cc9e1c',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '83d5e1e847e16e156d6ac68a2e2bc0700f29de37',
}

deps = {
  'glslang/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/glslang@{glslang_revision}',
  },

  'lunarg-vulkantools/src': {
    'url': '{chromium_git}/external/github.com/LunarG/VulkanTools@{lunarg_vulkantools_revision}',
  },

  'spirv-cross/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Cross@{spirv_cross_revision}',
  },

  'spirv-headers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Headers@{spirv_headers_revision}',
  },

  'spirv-tools/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Tools@{spirv_tools_revision}',
  },

  'vulkan-headers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Headers@{vulkan_headers_revision}',
  },

  'vulkan-loader/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Loader@{vulkan_loader_revision}',
  },

  'vulkan-tools/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Tools@{vulkan_tools_revision}',
  },

  'vulkan-utility-libraries/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Utility-Libraries@{vulkan_utility_libraries_revision}',
  },

  'vulkan-validation-layers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-ValidationLayers@{vulkan_validation_revision}',
  },
}
